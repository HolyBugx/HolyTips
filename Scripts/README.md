- **Quickly check for verb tampering issues:**
```bash
tamper() {
    echo -n "$1: "; for i in GET POST HEAD PUT DELETE CONNECT OPTIONS TRACE PATCH; \
        do echo "echo -n \"$i-$(curl -k -s -X $i $1 -o /dev/null -w '%{http_code}') \""; done \
        | parallel -j 5 ; echo
}
```

- **Quickly check for 403/401 & IP based restrictions bypass:**
```bash
xforward() {
 for method in 127.0.0.1 1; do
         echo $method: $(curl -k -s $1 -o /dev/null -H "X-Originating-IP: 127.0.0.1" -H "X-Forwarded-For: 127.0.0.1" -H "X-Forwarded-Host: 127.0.0.1" -H "X-Real-IP: 127.0.0.1" -H "X-Remote-IP: 127.0.0.1" -H "X-Remote-Addr: 127.0.0.1" -w '%{http_code} - %{size_download}')
 done
}
```

## Resources & Disclosed Reports 📝

**A collection of my favorite Bug Bounty Resources & Disclosed reports ordered by Vulnerability Types**

- [Starting out](#Starting-Out)
- [Books](#Books)
- [Blogs](#Blogs)
- [Training Platforms](#Training-Platforms)
- [Web Security](#Web-Security)
- [Recon](#Recon)
- [XSS](#XSS)
- [CSRF](#CSRF)
- [IDOR](#IDOR)
- [Open Redirect](#Open-Redirect)
- [Race Condition](#Race-Condition)
- [Subdomain Takeover](#Subdomain-Takeover)
- [SSRF](#SSRF)
- [XXE](#XXE)
- [SQLi](#SQLi)
- [Misc](#Misc)

---
## Starting-Out

- [PortSwigger's Learning Path](https://portswigger.net/web-security/learning-path)
- [Cobalt Vulnerability Wiki](https://cobalt.io/vulnerability-wiki/)
- [OWASP Top 10 Web Training](https://application.security/free/owasp-top-10)
- [OWASP Top 10 API Training](https://application.security/free/owasp-top-10-API)
- [Web Security Course](https://web.stanford.edu/class/cs253/)

---
## Books

- [The Web Application Hacker's Handbook, 2nd Edition](https://www.oreilly.com/library/view/the-web-application/9781118026472)
- [Web Hacking 101](https://leanpub.com/web-hacking-101)
- [Real-World Bug Hunting](https://www.amazon.com/gp/product/B072SQZ2LG)
- [The Tangled Web](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886)
- [The Hacker Playbook 2](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing-ebook/dp/B01072WJZE)
- [The Hacker Playbook 3](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing-ebook/dp/B07CSPFYZ2)

---
## Blogs

- [Assetnote](https://blog.assetnote.io/)
- [Secjuice](https://www.secjuice.com/)
- [James Kettle](https://skeletonscribe.net/)
- [Orange Tsai](https://blog.orange.tw/)
- [Sam Curry](https://samcurry.net/blog/)
- [Patrik Hudak](https://0xpatrik.com/)
- [Honoki](https://honoki.net/)

---
## Training-Platforms

- [BugBountyHunter.com](https://bugbountyhunter.com)
- [PentesterLab](https://pentesterlab.com)
- [HackTheBox](https://www.hackthebox.eu/home)
- [TryHackMe](https://tryhackme.com)
- [Rootme](https://www.root-me.org/?lang=en)
- [PicoCTF](https://picoctf.org)
- [GoogleCTF](https://capturetheflag.withgoogle.com)

---
## Web-Security

- [Finding The Origin IP Behind CDNs](https://zdresearch.com/finding-the-origin-ip-behind-cdns/)
- [Accessing cross-site data using JSONP](https://www.sjoerdlangkemper.nl/2019/01/02/jsonp/)
- [Hacking the SOP](https://medium.com/swlh/hacking-the-same-origin-policy-f9f49ad592fc)
- [LocalStorage vs Cookie XSS](https://academind.com/tutorials/localstorage-vs-cookies-xss/)
- [Cross-Site script inclusion](https://www.scip.ch/en/?labs.20160414)

---
## Recon

- [The Bug Hunter's Methodology v4.0 - Recon Edition](https://youtu.be/p4JgIu1mceI)
- [Fundamentals of Bug Bounty Recon](https://youtu.be/DABPWQ40yb0)
- [How To Do Recon: Introduction to Recon](https://youtu.be/o8L2nweiF1s)
- [Just another Recon Guide for Pentesters and Bug Bounty Hunters](https://www.offensity.com/de/blog/just-another-recon-guide-pentesters-and-bug-bounty-hunters/)
- [The Best Bug Bounty Recon Methodology](https://securib.ee/beelog/the-best-bug-bounty-recon-methodology/)
- [The Art of Subdomain Enumeration](https://appsecco.com/books/subdomain-enumeration/)

---
## XSS

- [Instagram Reflected XSS](https://ysamm.com/?p=695)
- [XSS in Facebook CDN](https://ysamm.com/?p=632)
- [XSS on forums.oculusvr.com](https://ysamm.com/?p=525)
- [Persistent DOM-based XSS in https://help.twitter.com via localStorage](https://hackerone.com/reports/297968)
- [DOM XSS on app.starbucks.com via ReturnUrl](https://hackerone.com/reports/526265)
- [XSS in steam react chat client](https://hackerone.com/reports/409850)
- [XSS while logging using Google](https://hackerone.com/reports/691611)
- [Stored XSS in RDoc wiki pages](https://hackerone.com/reports/662287)

---
## CSRF

- [CSRF on connecting Paypal as Payment Provider](https://hackerone.com/reports/807924)
- [CSRF on Periscope Web OAuth authorization endpoint ](https://hackerone.com/reports/215381)
- [CSRF combined with IDOR within Document Converter exposes files](https://hackerone.com/reports/398316)
- [CSRF in all API endpoints when authenticated using HTTP Authentication](https://hackerone.com/reports/195156)
- [The mass CSRFing of \*.google.com/\* products.](http://www.missoumsai.com/google-csrfs.html)
- [Facebook CSRF bug which lead to Instagram Partial account takeover.](https://ysamm.com/?p=379)
- [Media deletion CSRF vulnerability on Instagram](https://blog.darabi.me/2019/12/instagram-delete-media-csrf.html)
- [Facebook CSRF protection bypass which leads to Account Takeover](https://ysamm.com/?p=185)


---
## IDOR

- [IDOR bug to See hidden slowvote of any user even when you dont have access right](https://hackerone.com/reports/661978)
- [IDOR allow access to payments data of any user](https://hackerone.com/reports/751577)
- [IDOR Causing Deletion of any account](https://hackerone.com/reports/156537)
- [IDOR allow to extract all registered email](https://hackerone.com/reports/302485)
- [Another image removal vulnerability on Facebook](https://blog.darabi.me/2020/06/image-removal-vulnerability-on-facebook.html)
- [Gsuite Hangouts Chat 5k IDOR](https://secreltyhiddenwriteups.blogspot.com/2018/07/gsuite-hangouts-chat-5k-idor.html)
- [How I pwned a company using IDOR and Blind XSS](https://www.ansariosama.com/2017/11/how-i-pwned-company-using-idor-blind-xss.html)
- [Disclose Private Dashboard Chart's name and data in Facebook Analytics](https://bugreader.com/jubabaghdad@disclose-private-dashboard-charts-name-and-data-in-facebook-analytics-184)

---
## Open-Redirect

- [Open Redirects that matter](https://sites.google.com/site/bughunteruniversity/best-reports/openredirectsthatmatter)
- [XSS and Open Redirect on MoPub Login](https://hackerone.com/reports/683298)
- [XSS and Open Rredirect on supporthiring.shopify.com](https://hackerone.com/reports/158434)
- [Open Redirect in secure.showmax.com](https://medium.com/@ahmadbrainworks/bug-bounty-how-i-earned-550-in-less-than-5-minutes-open-redirect-chained-with-rxss-8957979070e5)
- [Open Redirect on streamlabs.com](https://hackerone.com/reports/978680)
- [Open Redirect on "Language change"](https://hackerone.com/reports/52035)
- [Open Redirect idp.fr.cloud.gov](https://hackerone.com/reports/387007)
- [Airbnb chaining third party open redirect into SSRF via liveperson chat](https://buer.haus/2017/03/09/airbnb-chaining-third-party-open-redirect-into-server-side-request-forgery-ssrf-via-liveperson-chat/)
- [Oauth authentication bypass on airbnb acquistion using wierd 1 char open redirect](https://xpoc.pro/oauth-authentication-bypass-on-airbnb-acquisition-using-weird-1-char-open-redirect/)

---
## Race-Condition

- [Race Condition in performing retest allows duplicated payments](https://hackerone.com/reports/429026)
- [Race Conditions in OAuth 2 API implementations](https://hackerone.com/reports/55140)
- [Race Condition in Flash workers may cause an exploitable double free](https://hackerone.com/reports/37240)
- [Exploiting a Race condition vulnerabililty](https://medium.com/@vincenz/exploiting-a-race-condition-vulnerability-3f2cb387a72)
- [Race Condition leads to undeletable group member](https://hackerone.com/reports/604534)
- [Race Condition on web](https://www.josipfranjkovic.com/blog/race-conditions-on-web)
- [Race Condition in account survey](https://hackerone.com/reports/165570)
- [Race Condition at create new Location](https://hackerone.com/reports/413759)

---
## Subdomain-Takeover

- [Subdomain Takeover to Authentication bypass ](https://hackerone.com/reports/335330)
- [Subdomain Takeover on happymondays.starbucks.com due to non-used AWS S3 DNS record](https://hackerone.com/reports/186766)
- [Subdomain Takeover on wfmnarptpc.starbucks.com](https://hackerone.com/reports/388622)
- [Subdomain Takeover on svcgatewaydevus.starbucks.com and svcgatewayloadus.starbucks.com](https://hackerone.com/reports/383564)
- [Subdomain Takeover: new level](https://medium.com/bugbountywriteup/subdomain-takeover-new-level-43f88b55e0b2)
- [Subdomain Takeover on svcardproxydevus.starbucks.com](https://hackerone.com/reports/380158)
- [Subdomain Takeover on blog.greenhouse.io pointing to Hubspot](https://hackerone.com/reports/38007)
- [Subdomain Takeover on openapi.starbucks.com](https://hackerone.com/reports/241503)

---
## SSRF

- [SSRF in Exchange leads to ROOT access in all instances](https://hackerone.com/reports/341876)
- [SSRF using Javascript allows to exfill data from Google Metadata](https://hackerone.com/reports/530974)
- [SSRF in Google cloud platform stackdriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/)
- [SSRF to ROOT Access](https://hackerone.com/reports/341876)
- [SSRF reading local files from downnotifier server](https://www.openbugbounty.org/blog/leonmugen/ssrf-reading-local-files-from-downnotifier-server/)
- [Facebook SSRF](https://medium.com/@amineaboud/10000-facebook-ssrf-bug-bounty-402bd21e58e5)
- [31k$ SSRF in Google Cloud Monitoring led to metadata exposure](https://nechudav.blogspot.com/2020/11/31k-ssrf-in-google-cloud-monitoring.html)
- [How I Chained 4 vulnerabilities on GitHub Enterprise, From SSRF Execution Chain to RCE!](http://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html)

---
## XXE

- [XXE at ecjobs.starbucks.com.cn](https://hackerone.com/reports/500515)
- [XXE on sms-be-vip.twitter.com in SXMP Processor](https://hackerone.com/reports/248668)
- [XXE and SSRF on webmaster.mail.ru](https://hackerone.com/reports/12583)
- [XXE in Site Audit function exposing file and directory contents](https://hackerone.com/reports/312543)
- [Blind OOB XXE on ubermovement.com](https://hackerone.com/reports/154096)
- [XXE over which leads to RCE](https://hackerone.com/reports/55431)
- [LFI and SSRF via XXE in emblem editor](https://hackerone.com/reports/347139)
- [Non-production Open Database In Combination With XXE Leads To SSRF](https://hackerone.com/reports/742808)

---
## SQLi

- [Bypassing a crappy WAF to exploit a blind SQLI](https://robinverton.de/blog/2019/08/25/bug-bounty-bypassing-a-crappy-waf-to-exploit-a-blind-sql-injection/)
- [Magix Bug Bounty: magix.com (RCE, SQLi) and xara.com (LFI, XSS)](https://www.rcesecurity.com/2014/04/magix-bug-bounty-magix-com-rce-sqli-and-xara-com-lfi-xss/)
- [Tesla Motors blind SQLI](https://bitquark.co.uk/blog/2014/02/23/tesla_motors_blind_sql_injection)
- [Blind SQL Injection on windows10.hi-tech.mail.ru](https://hackerone.com/reports/786044)
- [Blind SQLi leading to RCE, from Unauthenticated access to a test API Webservice](https://hackerone.com/reports/592400)
- [Step by Step Exploiting SQL Injection in Oculus](https://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html)
- [SQL Injection in lapsuudenturva](https://hackerone.com/reports/191146)
- [SQL Injection Root Access tw.yahoo.com](https://buer.haus/2015/01/15/yahoo-root-access-sql-injection-tw-yahoo-com/)



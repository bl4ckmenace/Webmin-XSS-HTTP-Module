# Webmin XSS HTTP-Module 🤖


Webmin version 1.995 and below have a critical security vulnerability that allows for bypassing referers, leading to cross-site scripting (XSS) attacks and the stealing of other users' cookies without detection. This vulnerability is particularly dangerous because users with the HTTP-Tunnel module permission can change the tunnel configuration, making it even easier for an attacker to exploit the vulnerability.

#### The affected URL is [https://example.com/tunnel/link.cgi/](https://example.com/tunnel/link.cgi/).

 #### A proof of concept video demonstrating the exploit can be found on YouTube at the following link: [https://youtu.be/i5MieKoY64Q](https://youtu.be/i5MieKoY64Q)

This vulnerability is a serious issue that should be addressed immediately by all Webmin users. If you are using Webmin version 1.995 or below, we recommend upgrading to the latest version as soon as possible. Additionally, you should be sure to monitor your network for suspicious activity and implement best practices for web application security, such as input validation and sanitization, to minimize the risk of XSS and cookie stealing attacks.

Please note that using a VPN or other security tools that can hide the referers is not enough to protect from this vulnerability.

## 🗒️References:

-   Webmin Security Announcement: [https://www.webmin.com/security.html](https://www.webmin.com/security.html)
-   OWASP Cross-Site Scripting (XSS) Prevention Cheat Sheet: [https://owasp.org/www-community/attacks/xss/](https://owasp.org/www-community/attacks/xss/)
-   OWASP Top 10 - A1: Injection: [https://owasp.org/top10/](https://owasp.org/top10/)

If you want to report a security issue, please reach out to Webmin team directly or via the contact form on their website.


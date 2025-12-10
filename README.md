# Webmin XSS HTTP-Module

Webmin versions **1.995 and below** have a vulnerability that lets an attacker bypass referrers and run XSS code.  
With this, an attacker can steal cookies or perform actions as another user.  
The issue is easier to exploit if the account has HTTP-Tunnel module permissions.

**Affected URL:**  
`https://example.com/tunnel/link.cgi/`

**POC video:**  
https://youtu.be/i5MieKoY64Q

If you are using an older Webmin version, update as soon as possible.  
Security tools like VPNs or anything that hides referrers are **not enough** to stop this attack.

### References
- https://www.webmin.com/security.html  
- https://owasp.org/www-community/attacks/xss/

If you need to report a security issue, contact the Webmin team directly.

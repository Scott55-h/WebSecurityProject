# Web SEcurity Project (Apache2 + ModSecurity)

This project setd up a secure web environment with two sites:
- **Static site**: studentName.upskills.ac.rw
- **Dynamic portfolio**: portfolio.upskills.ac.rw


Both are secured with HTTPS and ModSecurity (WAF), tested against common attacks:
- Directory Traversal
- Command Injection
- Cross-Site Scripting (XSS)
- SQL Injection

## Tech Stack
- Kali Linux (Debian-based)
- Apache2
- PHP + Mariadb
- ModSecurity + OWASP CRS
- UFW firewall + SSH 2FA

## Deliverables
- Apache configs
- Modsecurity configs
- Firewall + SSH configs
- Source code
- Database inserts
- Logs & screenshots 

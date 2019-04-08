class: middle, center

# OWASP Top 10

Version 2017

---

# Injection

* SQL
* NoSQL
* Operating System
* LDAP
* Other expression languages

---

# Broken Authentication

* Rate limiting
* Password complexity requirements
* Session timeouts
* Enumeration attacks

---

# Sensitive Data Exposure

* Encryption: no or poor usage
* Storing unnecessary data
* Weak algorithms
* Password hashing
* Predictable ids

---

# XML External Entities (XXE)

* Disable this feature!
* Avoid XML

---

# Broken Access Control

* Deny by default
* Minimize CORS
* Model owners instead of broad access
* Invalidate JWT after logout
* Keep audit log with monitoring

---

# Security Misconfiguration

* Default accounts/passwords
* Unpatched systems
* Debug features in production
* Security feature usage

---

# Cross-Site Scripting (XSS)

* User input directly output to scripts
* Similar to injection
* Rely on frameworks!
* EL inside URLs

---

# Insecure Deserialization

* Java deserialization of untrusted data
* Other languages too!
* Whitelists
* Signing
* Sandboxing deserialization

---

# Using Components with Known Vulnerabilities

* Update dependencies
* Remove unused dependencies
* Try [Dependabot](https://dependabot.com/)

---

# Insufficient Logging & Monitoring

* Keep audit trail
* Write useful diagnostic logs
* Monitor those logs!
* Evidence for authorities

---

# Further Reading

* [OWASP Top 10 2017](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf)

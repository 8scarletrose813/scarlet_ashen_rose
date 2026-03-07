# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly.

Please **do not create a public issue** for security vulnerabilities.

Instead, report them by contacting the project maintainer:

**Email:** [8scarlet.rose813@gmail.com](mailto:8scarlet.rose813@gmail.com)
or create a **private security advisory on GitHub**.

When reporting a vulnerability, please include:

* A clear description of the vulnerability
* Steps to reproduce the issue
* The potential impact
* Screenshots or proof-of-concept if possible

We will review the report and respond as soon as possible.

---

## Supported Versions

This project is currently under active development.

The website and codebase are typically **updated approximately once per month**, including improvements, fixes, and security updates.

| Version        | Supported       |
| -------------- | --------------- |
| Latest version | ✅ Supported     |
| Older versions | ❌ Not supported |

---

## Possible Security Risks

Because this project is a web-based platform with messaging and user interaction, the following vulnerabilities may potentially occur:

* Cross-Site Scripting (XSS)
* User impersonation
* Client-side data manipulation
* LocalStorage data exposure
* File upload abuse
* Spam or message flooding
* Unauthorized role changes

---

## Security Limitations

Some parts of this project run **entirely on the client side**, which means:

* Data may be stored in **LocalStorage**
* User roles may be manipulated by advanced users
* Uploaded files are **not automatically scanned for malware**
* There is currently **no server-side authentication system**

Because of this, the platform should **not be used for sensitive or confidential data**.

---

## Responsible Disclosure

Please allow reasonable time for investigation and fixing vulnerabilities before publicly disclosing them.

Responsible security research that helps improve the project is greatly appreciated.

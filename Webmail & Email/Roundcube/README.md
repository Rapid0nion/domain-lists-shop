# Roundcube Webmail

Roundcube is an open-source web-based IMAP email client written in PHP.

It provides a browser-based interface for accessing and managing email accounts through an existing mail server. Roundcube is widely deployed on shared hosting platforms, mail servers, VPS environments and enterprise infrastructures.

## Roundcube Security History

Roundcube has received numerous security fixes over the years. Reported vulnerabilities have included Cross-Site Scripting (XSS), Server-Side Request Forgery (SSRF), SQL injection, arbitrary file operations, code execution and other security issues.

Some notable CVEs affecting Roundcube include:

| CVE | Type | Affected versions / summary |
|---|---|---|
| [CVE-2026-54432](CVE-2026-54432.md) | Stored XSS | Stored XSS through an unescaped attachment MIME type |
| [CVE-2026-54433](CVE-2026-54433.md) | Stored XSS | Zero-click stored XSS in plain-text rendering |
| [CVE-2026-35540](CVE-2026-35540.md) | SSRF / Information Disclosure | CSS sanitization issue could allow requests to local network hosts |
| [CVE-2025-49113](CVE-2025-49113.md) | RCE | Authenticated remote code execution through PHP object deserialization |
| [CVE-2024-42009](CVE-2024-42009.md) | XSS | Crafted email could abuse HTML sanitization and affect email confidentiality/integrity |
| [CVE-2023-43770](CVE-2023-43770.md) | XSS | XSS through crafted links in text/plain email messages |
| CVE-2020-35730 | XSS | XSS through specially crafted plain-text email content |
| CVE-2020-15562 | XSS | XSS through crafted HTML email content |
| CVE-2020-12625 | XSS | XSS involving JavaScript in HTML message content |
| CVE-2020-12640 | LFI / Code Execution | Directory traversal involving plugin handling |
| CVE-2020-12641 | Command Injection | Command injection through image conversion configuration |
| CVE-2015-8793 | XSS | XSS through the `_mbox` parameter |
| CVE-2013-6172 | Multiple | Configuration manipulation that could lead to file disclosure, SQL injection and code execution |

## Recent Security Activity

Roundcube continues to receive security updates.

Recent releases have addressed vulnerabilities involving:

- XSS and HTML/CSS injection
- SSRF and local network resource access
- SQL injection
- arbitrary file deletion
- unsafe deserialization
- code injection
- remote image loading bypasses
- information disclosure

For example, Roundcube security releases in 2026 addressed several SSRF, XSS, CSS injection, SQL injection and arbitrary file operation issues.

## Why Roundcube Security Matters

Roundcube is often deployed as a public-facing webmail application. Because it handles email accounts and potentially sensitive communications, vulnerabilities in the application can have significant security implications.

Security researchers and defenders may therefore be interested in identifying Roundcube deployments, tracking affected versions and monitoring the security status of installations.

## Roundcube Domain Dataset

StemShop provides a domain dataset focused on Roundcube Webmail deployments.

The dataset is intended for:

- Security research
- Asset discovery research
- Technology analysis
- Internet-wide measurement
- Defensive security research
- Web infrastructure research

The dataset is provided as a structured collection of domain-level data.

### Dataset availability

A sample may be provided in this repository for research and evaluation.

The complete dataset is available through StemShop:

**https://stemshop.top/**

## Disclaimer

This dataset is provided for legitimate research, security analysis and defensive purposes.

The presence of a domain in a dataset does not establish that the associated system is vulnerable. Version detection and vulnerability assessment should be performed only on systems that you own or are explicitly authorized to test.

---

**StemShop — Domain Lists & Web Data**

https://stemshop.top/

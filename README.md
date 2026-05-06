# Web Application VAPT Report — aspnet.testsparker.com

Black-box penetration test on a real-world practice target.

## Target
- **URL:** http://aspnet.testsparker.com  
- **Type:** ASP.NET Web Application  
- **Assessment:** Black-box, 50 hours  

## Findings Summary
| Severity | Count |
|----------|-------|
| Critical | 3 |
| High | 4 |
| Medium | 5 |
| Low | 1 |

## Vulnerabilities Covered
- SQL Injection (Error-based, GET parameter) — CVSS 9.8
- Local File Inclusion (Path Traversal) — CVSS 8.8
- Stored & Reflected XSS — CVSS 7.4 / 6.1
- Publicly Accessible Database File (.mdb)
- FTP Log Disclosure
- IDOR / Unauthorized Product Listing
- Session Fixation
- Open Redirect
- Directory Listing, EXIF Metadata Leak, QR Code Exposure

## Tools Used
Nmap · Nikto · Burp Suite · SQLMap · Gobuster · exiftool · curl

## Methodology
OWASP Testing Guide + NIST 800-115

## Report
[📄 Download Full Report (PDF)](../../raw/main/VAPT_Report_Mayank_Kumar_Karn.pdf)
## Topics
`vapt` `penetration-testing` `owasp` `burpsuite` `sqlinjection` `xss` `lfi` `ethicalhacking`

## Disclaimer
Conducted on a legally authorized practice target for educational purposes only.

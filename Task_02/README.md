# Phishing-Email-Analysis (Repository)

**IMPORTANT:** This repository contains an educational example of a spoofing/phishing email used for defensive analysis. Use strictly for lab/training/documentation. Do NOT use for impersonation or fraud.

## Project Summary
- **Artifact analyzed:** `spoofing_mail.pdf`
- **Objective:** Identify phishing indicators, perform header analysis, extract suspicious URLs, and recommend mitigations.
- **Tools & Methods:** MXToolbox (header analyzer), command-line parsing (grep/sed), isolated sandbox for attachments, screenshots for provenance.

## Files in this repository
- `spoofing_mail.pdf` : Original uploaded PDF (canonical artifact).
- `phishing_email_raw.txt` : Plain-text extraction of PDF content (if available).
- `extracted_urls.txt` : URLs parsed from the email (if any).
- `extracted_hosts.txt` : Hostnames parsed from URLs (if any).
- `analysis_table.csv` : Structured findings & remediation recommendations.
- `screenshots/` : (placeholder) Add header analysis and inbox screenshots here.

## Findings (summary)
Refer to `analysis_table.csv` for a structured list of indicators, observations, evidence, and recommended actions.

## Recommended next steps
- Do NOT click links or open attachments on production hosts.
- Analyze attachments only in an isolated sandbox and document findings (save as `attachment_analysis.txt`).
- Quarantine the sample at mail gateway, block sender domains/IPs, and report to the impersonated vendor.

## Author
Vedant — B.Tech Cybersecurity (DY Patil University)

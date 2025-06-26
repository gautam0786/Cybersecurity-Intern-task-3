# 🛡️ PC Vulnerability Scan - Internship Task 3

## 📌 Objective

To perform a basic vulnerability assessment on my local PC using a free tool and identify common security risks.

---

## 🧰 Tools Used

- Tool: [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)  
  *(Alternatively: OpenVAS Community Edition)*
- Platform: Windows 10 / Linux (specify)
- Target: Localhost (`127.0.0.1`) / Internal IP

---

## 🧭 Steps Performed

1. Installed Nessus Essentials and activated with a free key.
2. Launched the tool at `https://localhost:8834` and configured scan.
3. Set up a Basic Network Scan on my PC (local IP).
4. Started and waited for scan completion (approx. 45 mins).
5. Reviewed vulnerabilities sorted by severity.
6. Researched top 3 critical vulnerabilities and documented fixes.
7. Took screenshots of scan results and vulnerability details.
8. Created this GitHub repository with documentation and screenshots.

---

## 📑 Summary of Findings

| CVE ID         | Severity | Description                                     | CVSS Score | Mitigation Summary         |
|----------------|----------|-------------------------------------------------|------------|-----------------------------|
| CVE-2021-34527 | Critical | PrintNightmare vulnerability in Windows Print Spooler | 8.8        | Disable Print Spooler service |
| CVE-2022-22965 | High     | Spring4Shell – Remote Code Execution in Spring Core | 9.8        | Upgrade to patched version |
| CVE-2020-0601  | Medium   | Windows CryptoAPI spoofing vulnerability        | 7.5        | Apply security patch (KB4528760) |



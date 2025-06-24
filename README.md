# 🛡️ Cyber Security Internship – Task 2: Phishing Email Analysis

## 📌 Objective

The objective of this task is to analyze a suspicious email that impersonates Microsoft Office 365. The analysis aims to identify phishing indicators, assess potential risks, and document how such attacks use social engineering to deceive users.

This task is part of a hands-on cybersecurity internship designed to enhance practical threat detection skills.

---

## 📩 Email Overview

- **Subject:** High-severity alert: Phish delivered due to tenant or user override  
- **Sender:** microsoft@email-records.com (spoofed domain)  
- **Date:** January 22, 2021  
- **Platform Targeted:** Microsoft Office 365  
- **Attack Type:** Brand spoofing, phishing, social engineering  

---

## 🔍 Key Findings from the Analysis

### ✅ 1. **Spoofed Domain**
The email appears to originate from `@email-records.com`, which is not an official Microsoft domain. Authentic alerts come from trusted sources like `@microsoft.com` or `@protection.outlook.com`.

### ✅ 2. **Brand Impersonation**
The attacker mimics Microsoft Office 365 branding to make the email look credible. This includes use of logos, layout, and tone.

### ✅ 3. **Urgency-Based Language**
The subject line and message stress "high-severity" to invoke fear and prompt immediate action from the recipient.

### ✅ 4. **Unverified Call to Action**
A “View alert details” button encourages the user to click, likely redirecting to a fake login page or malware-laced site.

### ✅ 5. **Lack of Personalization**
No recipient name, account ID, or organization is mentioned—common traits in mass phishing emails.

### ✅ 6. **Inconsistent Timestamps**
The email references different timestamps (4:22 PM and 9:22 PM), a detail often overlooked in fake alerts.

### ✅ 7. **Generic Sign-Off**
The email is signed simply as “The Office 365 Team” without any contact information or support links.

---

## 🔐 Security Risk Assessment

If a user interacts with the email’s malicious link:

- **Credential Theft:** Stolen Office 365 login info  
- **Account Compromise:** Email hijack, lateral phishing  
- **Malware Infection:** Remote access tools or trojans  
- **Data Leakage:** Exfiltration of internal company data

---

## 📁 Repository Structure

| File Name                          | Description                                        |
|-----------------------------------|----------------------------------------------------|
| `Phishing_Email_Analysis_Report.pdf` | Full technical analysis report                     |
| `Screenshot.png`                  | Image of the phishing email used for the analysis |
| `README.md`                       | Project summary and documentation                 |

---

## ✍️ Author

**Rajarshi Chakraborty**  
Cyber Security Intern  
GitHub: [@X5464](https://github.com/X5464)

---

## 📨 Internship Task Submission

This GitHub repository was created and submitted as part of **Task 2** of the Elevate Cyber Security Internship.  
It demonstrates practical knowledge in phishing detection, technical writing, and GitHub documentation.


---

> ✅ *Note: All personally identifying information, IPs, and links have been sanitized for privacy and security.*

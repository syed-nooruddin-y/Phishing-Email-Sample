# 🛡️ Phishing Email Sample – Analysis Project

This repository contains a phishing email analysis project demonstrating detection of spoofed senders, suspicious links, header verification issues, urgency indicators, and common phishing traits based on an online sample.

---

## 🔐 Features

- **Analyzes phishing emails step-by-step**  
  Implements an 8-stage investigation method to break down every part of a suspicious email.

- **Inspects sender information for spoofing**  
  Checks whether the sender’s domain is legitimate or impersonated.

- **Evaluates availability and authenticity of email headers**  
  Identifies missing or fake header fields such as SPF, DKIM, and DMARC.

- **Flags suspicious buttons and embedded links**  
  Detects fake login screens, unverifiable URLs, and phishing redirects.

- **Identifies urgency and social-engineering triggers**  
  Highlights fear-based or action-forcing messages used to manipulate victims.

- **Checks for mismatched or misleading URLs**  
  Compares visible link text with expected official domains.

- **Assesses writing quality and formatting**  
  Notes inconsistencies that may indicate low-quality phishing attempts.

- **Generates a clear summary of phishing traits**  
  Provides a final verdict listing all red flags and indicators of compromise.

---

## 📘 What I Learned 

### 🔹 1. How phishing samples are obtained  
I learned how phishing emails are collected from trusted cybersecurity training sites and how attackers structure fake messages.

### 🔹 2. Identifying spoofed sender addresses  
I learned how to verify whether a sender domain is official or impersonated.  
In this sample, **wise.promotions@webnotifications.net** is *not* an official Wise domain.

### 🔹 3. The role of email headers  
I learned what email headers contain (Return-Path, Received, SPF, DKIM, DMARC) and how they help prove authenticity.  
This sample did not include raw headers, so I learned how to properly document that limitation.

### 🔹 4. Detecting suspicious links  
I learned that phishing emails often use login buttons or hyperlinks that visually appear safe but redirect to malicious websites.  
Since screenshots cannot show hover URLs, I learned how to treat such links as suspicious.

### 🔹 5. Spotting urgent or threatening language  
I recognized how phishing messages use urgency or fear (“Log in”, “Sign up now”, “Action required”) to push victims into quick actions.

### 🔹 6. Finding mismatched URLs  
I learned to compare visible link text with expected domains and detect mismatched, unusual, or misleading URLs.

### 🔹 7. Checking grammar and writing style  
I learned that phishing messages may contain correct or incorrect grammar, but grammar alone cannot confirm legitimacy.

### 🔹 8. Summarizing phishing traits  
I learned to combine all findings into a structured conclusion including spoofed domains, suspicious buttons, urgency tactics, URL mismatch, and missing headers.

**Overall:**  
I learned how to systematically analyze a phishing email using an 8-step method and document every finding clearly and professionally.

---

## 📝 Summary of Findings

From the phishing sample:

- Sender domain is fake and does not belong to Wise  
- Email header unavailable (sample displayed on webpage only)  
- Contains a fake login button designed to steal credentials  
- Uses manipulative / action-forcing language  
- Domain and visual content do not match official Wise branding  
- Fake login screen imitates the real website  

---

## ✅ Final Conclusion

**The sample is a phishing attempt designed to harvest user login details and steal sensitive information.**

---

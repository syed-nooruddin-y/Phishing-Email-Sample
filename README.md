# Phishing-Email-Sample
Phishing email analysis project demonstrating detection of spoofed senders, suspicious links, header verification issues, urgent language indicators, and phishing traits based on an online sample.



## 🚀 How To Use

1. Clone or download the repository  
2. Open **README.md** to read the full analysis  
3. View screenshots in the `/screenshots` folder  
4. Use this repo as a reference for cybersecurity assignments or practice  



## 🔐 Features

- **Analyzes phishing emails step-by-step**  
  Follows an 8-stage investigation method to break down every part of a suspicious email.

- **Inspects sender information for spoofing**  
  Verifies whether the sender’s domain is legitimate or impersonated.

- **Evaluates availability and authenticity of email headers**  
  Identifies missing or fake header fields such as SPF, DKIM, and DMARC.

- **Flags suspicious buttons and embedded links**  
  Detects fake login pages, unverifiable URLs, and phishing redirects.

- **Identifies urgency and social-engineering triggers**  
  Highlights fear-based or action-forcing messages used to manipulate the victim.

- **Checks for mismatched or misleading URLs**  
  Compares visible link text with expected domains to identify deception.

- **Assesses the email for grammar and formatting abnormalities**  
  Notes inconsistencies that indicate low-quality phishing attempts.

- **Generates a clear summary of phishing traits**  
  Produces a final assessment listing all red flags and a verdict on whether the email is malicious.


## 📘 What I Learned 
### 🔹 1. How to obtain phishing samples  
I learned how phishing emails can be found on trusted cybersecurity training websites and how attackers design fake messages.

### 🔹 2. Identifying spoofed sender addresses  
I understood how to check the sender email and verify whether the domain is legitimate.  
HERE wise.promotions@webnotifications.net  is not an official Wise domain.

### 🔹 3. Role of email headers in verification  
I learned what email headers contain (Return-Path, Received, SPF, DKIM, DMARC) and how they help verify message authenticity.  
In this sample, real headers were not available, so I learned how to document that limitation.

### 🔹 4. Detecting suspicious links  
I learned that phishing emails often use login buttons or hyperlinks that look normal but point to malicious sites.  
Since screenshots cannot show hover URLs, I learned how to flag such links as suspicious.

### 🔹 5. Spotting urgent or threatening language  
I recognized how phishing messages create urgency or fear (e.g., “Log in”, “Sign up now”, “Action required”) to push the user into clicking.

### 🔹 6. Finding mismatched URLs  
I learned how to compare visible links with actual URLs and how mismatched or odd-looking domains are strong phishing indicators.

### 🔹 7. Checking grammar and writing style  
I learned that phishing emails may use correct or incorrect grammar, but grammar alone cannot determine legitimacy.

### 🔹 8. Summarizing phishing traits  
I learned how to combine all findings into a clear summary that highlights spoofed domains, suspicious buttons, urgency techniques, URL mismatch, and lack of real headers.

**Overall, I learned how to systematically analyze a phishing email using an 8-step structured method and document every finding clearly.**



## 📝 Summary of Findings

From the phishing sample:

- **Sender domain is fake** and does not belong to Wise  
- **Email header not available**, since the sample was displayed on a webpage  
- Contains a **fake login button** designed to steal credentials  
- Uses **manipulative / action-forcing language**  
- Domain and visual content **do not match official Wise branding**  
- Fake login screen imitates the real website  

**Overall Conclusion:**  
The sample is a phishing attempt built to harvest user login details.

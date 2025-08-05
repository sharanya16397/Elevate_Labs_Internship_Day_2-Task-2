# 📄 Phishing Email Analysis – Task 2 (Cybersecurity Internship)

## 🎯 Objective

To analyze a suspicious email and identify phishing characteristics including spoofed sender addresses, fake URLs, urgent language, and lack of professional formatting, using an Amazon shipping confirmation phishing email.

---

## 🛠️ Tools Used

- Sample Phishing Email (Amazon Shipping Confirmation)  
- Header Analysis Tool: [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)  
- Browser (for link hover analysis)  
- Manual inspection based on known phishing traits  

---

## 📨 Step-by-Step Analysis

### ✅ Step 1: Sender’s Email Address (Spoofing Check)
- The sender domain is not from a legitimate `@amazon.com` address.
- Likely spoofed using a public email like `@gmail.com` or a fake domain.
- 📌 **Conclusion:** Spoofed sender detected.

### ✅ Step 2: Email Header Check
- Not available in this case (image-based sample).
- In real emails, use header tools to check SPF, DKIM, and IP address discrepancies.

### ✅ Step 3: Suspicious Links or Attachments
- The "order number" or delivery link is likely clickable.
- Phishing emails commonly redirect to fake websites like `amazon-support-verify.com`.

### ✅ Step 4: Urgent or Threatening Language
- Email pretends that an unauthorized order has been made.
- This creates urgency or panic to make the user click immediately.

### ✅ Step 5: Mismatched URLs
- Hovering over links (in real emails) often shows a domain different from the displayed one.
- In phishing emails, these usually redirect to a fraudulent login page.

### ✅ Step 6: Spelling or Grammar Errors
- The greeting says “Hello ,” — there's an extra space and no name.
- Lack of personalization is a red flag.

### ✅ Step 7: Missing Branding and Security Features
- Missing Amazon footer, digital signature, or proper unsubscribe link.
- These elements are typically found in real Amazon emails.

---

## 🔎 Summary of Phishing Traits

| #  | Indicator             | Description                                                   |
|----|------------------------|---------------------------------------------------------------|
| 1  | Spoofed Sender         | Uses a fake or public domain instead of official `@amazon.com` |
| 2  | Urgent Setup           | Claims your account was charged to create panic              |
| 3  | Suspicious Links       | Hidden or fake domains disguised as order confirmation links |
| 4  | Generic Greeting       | Uses “Hello ,” without any personalization                   |
| 5  | Mismatched URLs        | Displayed links differ from actual link destination          |
| 6  | Styling Issues         | Minor formatting issues reveal unprofessional appearance     |
| 7  | Missing Security Info  | No signature, branding, or unsubscribe links                 |



> 🔐 Stay alert. Think before you click.

# Phishing Email Analysis Report

## 📩 Sample Email Summary
A suspicious email claiming to be from "PayPal Security" with urgent language asking the recipient to verify their identity.

---

## 🧪 Step-by-Step Analysis

### 1. Examine Sender’s Email Address for Spoofing
- **Claimed Sender**: security@paypa1.com
- **Observation**: The domain "paypa1.com" (with number 1 instead of "l") is a spoofed version of the real "paypal.com".
- ✅ **Spoofing detected**

---

### 2. Check Email Headers for Discrepancies
- **Headers show multiple mismatches** in return paths and sender IP addresses.
- Used online header analyzer (like MXToolbox) to trace email flow.
- ✅ **Header anomalies confirmed**

---

### 3. Identify Suspicious Links or Attachments
- The main link text shows a "paypal.com" domain.
- Actual link is: `http://paypal.com.verify-user-update-security.com/login`
- ✅ **URL is misleading and highly suspicious**

---

### 4. Look for Urgent or Threatening Language
- Phrases like “verify immediately” and “account will be suspended”.
- ✅ **Urgency used to provoke action**

---

### 5. Note Any Mismatched URLs (Hover Analysis)
- **Displayed**: http://paypal.com
- **Actual**: http://paypal.com.verify-user-update-security.com/login
- ✅ **Hover mismatch confirms phishing intent**

---

### 6. Verify Presence of Spelling or Grammar Errors
- Sentence: “Failure to verify will result in suspension of your account.” is grammatically awkward.
- ✅ **Grammar issues found**

---

### 7. Summarize Phishing Traits Found
- Spoofed domain used in sender address.
- Suspicious and misleading URL.
- Urgent tone pushing for action.
- Header discrepancies showing origin mismatch.
- Poor grammar and formatting.
- ✅ **Email confirmed as phishing attempt**

---

## 🎯 Conclusion
This email exhibits all major phishing characteristics and should be reported to the security team and marked as spam.


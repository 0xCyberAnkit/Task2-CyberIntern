# Phishing Email Analysis

## Overview
This report analyzes a set of email samples to identify phishing characteristics. Each email is labeled as either phishing or legitimate, with reasoning based on common threat indicators.

---

## ✅ Legitimate Emails

1. **Planned maintenance notice**
   - Sender domain matches organization.
   - No suspicious links or requests.
   - Informational tone, no urgency.

2. **Weekly team update**
   - Internal sender and content.
   - No action required, no sensitive data requested.

---

## 🚨 Phishing Emails & Indicators

1. **Payroll correction request**
   - Spoofed HR identity.
   - Requests sensitive banking info.
   - Uses Gmail instead of company domain.

2. **Security re-login**
   - External domain (`service-update.com`) not affiliated.
   - Urgent tone and credential harvesting link.

3. **Overdue invoice**
   - Link points to `paypel` (typo of PayPal).
   - Domain mismatch and urgency.

4. **Gift card favor**
   - Unusual financial request.
   - Likely compromised legitimate contact.

5. **Survey link**
   - Suspicious third-party domain.
   - No verification of sender.

6. **Macro-enabled invoice**
   - ZIP attachment with macro instructions.
   - Common malware delivery method.

7. **Refund offer**
   - Requests personal and banking info.
   - Too-good-to-be-true reward.

8. **Account suspension notice**
   - Urgent scare tactics.
   - Link likely leads to credential theft.

9. **CEO wire transfer**
   - Executive impersonation.
   - Urgent financial request.

10. **Job onboarding**
    - Requests national ID and bank details.
    - Unverified sender and domain.

11. **Password reset**
    - Redirects to malicious domain.
    - Claims suspicious activity to induce panic.

---

## 🔧 Tools Used
- Manual inspection
- Domain reputation checks
- Link hover verification
- Header analysis (optional)

---

## 🧠 Key Takeaways
- Always verify sender domains.
- Hover over links before clicking.
- Be cautious of urgent or emotional language.
- Never share sensitive info via email.

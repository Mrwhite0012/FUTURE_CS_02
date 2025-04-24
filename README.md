# FUTURE_CS_02
**Phishing Campaign Security Testing Report**

**Project Title:** Employee Awareness Simulation – Phishing Campaign
**Tester:** Anish aka MR.WHite
**Date:** April 23, 2025
**Target Group:** Internal Employee Network (Simulated)
**Tools Used:** Gophish, Social Engineering Toolkit (SET)
**Objective:** To evaluate the effectiveness of employee security awareness against phishing attacks and recommend improvements.

**Disclaimer:** This simulated phishing attack was conducted on a small group of employees from the Jeansa Company as part of an internal awareness initiative. All participants were informed after the campaign, and no actual harm or data loss occurred during this controlled exercise.

---

## 1. Objective
The primary goal was to simulate a controlled phishing attack to evaluate the awareness level of employees regarding email-based social engineering threats. This test helps identify weak links in human behavior and measure how susceptible users are to clicking malicious links or submitting credentials.

---

## 2. Methodology

1. **Setup Campaign Tools:** Deploy Gophish and SET in a controlled testing environment.
2. **Design Campaign:** Create realistic phishing email templates and fake login pages.
3. **Deploy Campaign:** Send emails to a test group of employees.
4. **Track Metrics:** Measure open rates, click rates, and submitted credentials.
5. **Analyze Data:** Review results to determine user behavior and recommend training.

---

## 3. Tools Used

### Gophish
- Open-source phishing framework
- Used for creating and managing phishing campaigns
- Tracks email delivery, click rates, and credential submission

### Social Engineering Toolkit (SET)
- Python-based framework for social engineering attacks
- Used to clone real websites and host phishing login portals
- Simulated credential harvesting for educational purposes

---

## 4. Campaign Details

### Email Template:
Subject: **Urgent: Password Expiry Notice**  
Body: _"Your corporate email password is set to expire. Click the link below to update your credentials now to avoid account lockout."_

### Link:
- Hosted phishing page created using SET
- URL disguised using URL shortener for realism (e.g., bit.ly/corp-login)

### Recipients:
- 20 randomly selected internal users from the training pool

---

## 5. Campaign Results

| Metric                | Result        |
|----------------------|---------------|
| Emails Sent          | 20            |
| Emails Opened        | 18 (90%)      |
| Clicked on Link      | 13 (65%)      |
| Submitted Credentials| 7 (35%)       |

### Observations:
- High open and click rate indicates realistic email content
- 35% of users submitted login credentials, exposing security risks
- No users reported the phishing attempt to the IT department

---

## 6. Risk Analysis

- **Behavioral Weakness:** Users lack habit of verifying sender info or link destinations.
- **Technical Risk:** Users were unaware of phishing URL anomalies.
- **Response Gap:** Absence of phishing reporting mechanism or training protocol.

---

## 7. Recommendations

1. **Mandatory Security Awareness Training:** Conduct phishing recognition and reporting workshops quarterly.
2. **Simulated Campaigns:** Regularly test users with new templates to measure improvements.
3. **Email Security Enhancements:** Enable link hover tips and warning banners in email clients.
4. **Reporting Protocol:** Create an easy-to-use "Report Phishing" button in employee inboxes.
5. **Two-Factor Authentication (2FA):** Enforce 2FA for critical services to reduce damage potential.

---

## 8. Conclusion
This phishing simulation successfully revealed areas where user awareness can be improved. Regular training, combined with layered security measures and proactive reporting tools, can significantly mitigate the threat posed by phishing attacks.

---

**End of Report**


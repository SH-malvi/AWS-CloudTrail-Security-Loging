# AWS-CloudTrail-Security-Loging
Enabled CloudTrail to monitor all AWS activities and stored log securely  in S3 for security auditing 
# AWS-CloudTrail-Security-Logging

## 📌 Project Overview
Implemented AWS CloudTrail to monitor and audit all AWS activities. This acts as a CCTV for your AWS account - it logs who did what, when, and from where. Logs are securely stored in S3 for security analysis.

## 🎯 Why this project is important?
In real companies, if someone deletes a server or steals data, we need proof. CloudTrail gives that proof. It is a must-have for SOC Analyst and Cloud Security roles.

## 🛠️ What I Did

**Step 1: Created Secure S3 Bucket for Logs**
- Bucket Name: `shraddha-cloudtrail-logs-2026`
- Enabled: Block All Public Access (Security Best Practice)
- Enabled: Server-Side Encryption

**Step 2: Enabled CloudTrail**
- Trail Name: `shraddha-security-trail`
- Management Events: Enabled (Read/Write)
- S3 Bucket: `shraddha-cloudtrail-logs-2026`
- Log File Validation: Enabled

**Step 3: Verified Security Logging**
- Checked CloudTrail Dashboard -> Status: Logging
- Checked S3 Bucket -> Logs are arriving in `AWSLogs/` folder

## 📸 Screenshots
1. CloudTrail Dashboard showing Logging Enabled
2. S3 Bucket showing log files

## 🔐 Security Best Practices Used
- Least Privilege - Only admin can access trail
- S3 Block Public Access - Logs are private
- Log File Validation - No one can tamper logs
- Encryption - Logs encrypted at rest

## 🎓 What I Learned
- How to enable continuous security monitoring
- How SOC teams use CloudTrail for incident investigation
- S3 + CloudTrail integration

## 👩‍💻 Author
**Shraddha Malvi** - Biology Teacher turned Cloud Aspirant
Location: Seoni, MP
GitHub: SH-malvi
Skills: AWS IAM, S3, CloudTrail, MFA

#AWS #CloudSecurity #SOC #CloudTrail #WomenInTech

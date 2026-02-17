# password-auditing-lab-l0phtcrack
This project demonstrates a hands-on Password Security Assessment performed using L0phtCrack in a controlled lab environment.
The objective of this lab was to understand how weak passwords can be identified and cracked, and how Security Operations Center (SOC) teams detect and mitigate such risks.

🎯 Objective

Perform password auditing on a Windows 10 virtual machine

Identify weak credentials using dictionary-based attacks

Analyze password strength patterns

Understand risk from a Blue Team perspective

🛠 Lab Environment

Windows 10 Virtual Machine

L0phtCrack 7

Local User Accounts (Test Environment Only)

🔍 Activities Performed
1️⃣ Quick Password Audit

Imported local account hashes

Initiated automated audit scan

2️⃣ Dictionary-Based Password Attack

Used wordlist to simulate brute-force/dictionary attack

Identified weak and predictable passwords

3️⃣ Password Pattern Analysis

Observed common weaknesses:

Numeric-only passwords

Dictionary-based passwords

Predictable patterns (e.g., Name@123)

4️⃣ Report Generation

Generated HTML audit report

Reviewed cracked credentials and risk severity

📊 Key Findings

Numeric-only passwords were cracked within seconds

Common dictionary words were easily compromised

Predictable patterns significantly increased attack success rate

🛡 Security Risks Identified

Weak credentials can lead to:

Unauthorized access

Privilege escalation

Lateral movement within the network

Potential domain compromise

🔐 SOC-Level Insights

This lab provided understanding of:

✔ Importance of enforcing strong password policies
✔ Account lockout policy configuration
✔ Monitoring failed login attempts (Event ID 4625)
✔ Detecting brute-force patterns through log analysis
✔ Security baseline enforcement

🧠 Defensive Recommendations

Enforce complex password policy

Implement account lockout threshold

Monitor authentication logs

Enable multi-factor authentication (MFA)

Conduct periodic password audits

⚠ Disclaimer

This lab was conducted strictly in a controlled virtual environment for educational purposes only.

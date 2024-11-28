Objective
To expand on foundational knowledge by introducing network monitoring, secure
authentication, and vulnerability scanning. Interns will engage in hands-on tasks to deepen their
understanding of practical cybersecurity tools and techniques.
Week 2 Task: Network Monitoring, Authentication Security, and
Vulnerability Analysis

Task Breakdown
1. Network Monitoring and Intrusion Detection
Objective: Understand and utilize tools for monitoring network activity and detecting suspicious
behavior.
Tasks:
● Install and Configure Snort:
○ Install Snort, an open-source intrusion detection system (IDS), on the VM set up
in Week 1.

○ Configure Snort to monitor network traffic and detect suspicious activities.
● Test Snort with Simulated Attacks:
○ Use a safe tool like hping3 to simulate different types of network traffic (e.g.,
SYN flood, ICMP flood).
○ Review Snort logs to identify the simulated traffic.
Deliverable:
● Screenshots of Snort configuration and logs showing detected activity.
● A brief explanation of how Snort identifies suspicious traffic and its significance in
network security.

2. Two-Factor Authentication (2FA) Implementation
Objective: Learn how to implement and test basic two-factor authentication for enhanced
security.
Tasks:
● Install an Open Source 2FA Tool:
○ Use tools like Google Authenticator or FreeOTP along with PAM (Pluggable
Authentication Module) to set up 2FA on your VM.
● Test 2FA Implementation:
○ Attempt to log in to the VM and demonstrate that the second authentication factor
is required.
● Explain the Benefits of 2FA:
○ Research and summarize the importance of 2FA in securing user accounts.
Deliverable:
● Screenshots showing successful 2FA implementation and testing.
● A 1-page write-up explaining the benefits and challenges of 2FA.

3. Vulnerability Scanning
Objective: Identify vulnerabilities in systems using a vulnerability scanner.
Tasks:
● Install and Run OpenVAS:
○ Install OpenVAS (or Nessus Community Edition if OpenVAS is unavailable) on
your VM.
○ Perform a vulnerability scan on your VM and analyze the results.
● Document Vulnerabilities:
○ Select three vulnerabilities identified in the scan.
○ Explain their potential impact and suggest mitigation strategies.
Deliverable:
● Screenshots of the OpenVAS scan results.
● A 1-page report summarizing the three vulnerabilities and mitigation strategies.

4. Basic Cryptography: Encryption and Decryption
Objective: Understand encryption concepts by implementing basic encryption and decryption.
Tasks:
● Write a Python Script:
○ Use Python to encrypt and decrypt a sample message using the AES algorithm
(you may use libraries like pycryptodome).
● Demonstrate Secure Key Management:
○ Explain the importance of secure key storage and management.
Deliverable:
● Python script code for encryption and decryption.
● A short write-up explaining how encryption ensures confidentiality.

6. Threat Analysis: Real-World Case Study
Objective: Analyze a real-world cybersecurity incident to understand the lifecycle of an attack.
Tasks:
● Research a recent cybersecurity incident (e.g., a ransomware attack, data breach).
● Write a case study covering:
○ The nature of the attack.
○ The vulnerabilities exploited.
○ The impact and resolution.
● Suggest measures that could have prevented the attack.
Deliverable:
● A 2-page case study document summarizing the incident, impact, and prevention
measures.

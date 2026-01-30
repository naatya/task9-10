# task9-10
 Network Vulnerability Scanning

**Project Overview**
I performed a security assessment focusing on SQL Injection and Network Scanning. The goal was to identify vulnerabilities, analyze their impact, and suggest security fixes.

**What I Did (Step-by-Step)**

**Network Discovery:** Scanned the local network to find active devices and mapped their IP addresses.

**Service & Port Scanning:** Identified open ports and detected the software versions (services) running on the target system.

**OS Fingerprinting**: Analyzed the target to identify its Operating System.

**Vulnerability Identification:** Used manual methods and tools like SQLMap to find injectable parameters in web applications.

**Data Extraction:** Successfully demonstrated how sensitive data (like database names and tables) can be extracted if the system is not secured.

**7. Risk Interpretation (Simple English)**

**Data Theft**: The biggest risk is a "Data Breach," where an attacker can steal usernames, passwords, and private company data.

**System Takeover**: Outdated software versions (like old FTP or Apache) allow hackers to take full control of the server.

**Unsafe Communication:** Using unencrypted ports (like HTTP instead of HTTPS) means anyone on the network can see the login details.

**Service Downtime**: Vulnerabilities can be used to crash the database, causing the business to stop working.

**8. Documentation of Findings**

Technical Evidence: All scan results and database structures were saved in a file named scan_report.txt.

**Key Discovery:** Found that the application was vulnerable to SQL Injection because it was not filtering user input properly.

**Solution Provided**: Recommended the use of Prepared Statements and Input Validation to block such attacks.

**Conclusion:** The assessment proves that regular updates and secure coding practices are necessary to protect the company's digital assets.

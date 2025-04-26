# FinalCS305
# Secure Software Practices for Artemis Financial

## 1. Client Overview  
**Who was the client? What issue did the company want you to address?**  
Artemis Financial is a financial services firm that manages highly sensitive customer data through a web portal. They needed to eliminate unencrypted HTTP endpoints and remove outdated third-party libraries to prevent data interception and tampering.

## 2. Findings and Value of Secure Coding  
**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**  
I applied SHA-256 hashing for data integrity, upgraded all traffic to HTTPS with RSA-2048 certificates, and ran automated scans to purge vulnerable dependencies. Coding securely stops costly breaches and avoids regulatory fines, while building client trust—a critical asset in finance that supports long-term growth.

## 3. Assessment Challenges  
**Which part of the vulnerability assessment was challenging or helpful to you?**  
Refactoring encryption routines without breaking existing tests was the toughest part. That challenge highlighted gaps in our test coverage and motivated me to write clearer tests and documentation, which ultimately made the codebase more robust.

## 4. Layered Security and Future Tools  
**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**  
I combined hashing, strong encryption, certificate-based authentication, and dependency checks to form a multi-layer defense. Going forward, I’d integrate SonarQube for static analysis, OWASP ZAP for dynamic scanning, and regular threat modeling to prioritize the most effective mitigations.

## 5. Verification and Regression Testing  
**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**  
After each refactoring step, I reran unit and integration tests and repeated dependency-check scans. This continuous testing cycle caught any new issues right away, ensuring the application stayed both functional and secure.

## 6. Resources and Practices  
**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**  
I leaned on the OWASP Top Ten framework, secure-by-design principles, automated certificate-generation tools, and modern dependency-management scanners. These practices form a reusable toolkit for any future secure-coding project.

## 7. Artifacts for Employers  
**What might you show future employers from this assignment?**  
I can share the full secure-software report, before-and-after Git commits in the refactored repository, detailed vulnerability-scan reports, and updated test suites that demonstrate how each security gap was identified and closed.

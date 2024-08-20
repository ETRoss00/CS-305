# CS-305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that specializes in developing individualized financial plans for its customers, including savings, retirement, investments, and insurance. The company wanted to modernize its operations by making sure that its custom software was up-to-date with the latest security protocols. Artemis Financial also required the addition of a file verification step within its web application to ensure secure communications. The key issue addressed was enhancing the security of data transfers by implementing a cryptographic hash algorithm and securing the application’s communications through HTTPS.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

When I identified security vulnerabilities within the application, I implemented industry-standard encryption algorithms (SHA-256 for checksum verification) and configured HTTPS for secure communications. Coding securely is important because it protects the company’s sensitive data from being compromised by cyber threats. Secure coding practices also contribute to the overall reliability and trustworthiness of the software. For a company like Artemis Financial, which handles sensitive financial data, software security is vital to maintaining client trust, avoiding potential data breaches, and complying with regulatory requirements.

Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging yet helpful part of the vulnerability assessment was using the Dependency-Check tool to analyze third-party libraries for known vulnerabilities. This process was important because it highlighted potential risks that might have been overlooked, such as a vulnerability in the 'spring-web' library. Addressing these vulnerabilities required not only technical understanding but also strategic planning to mitigate risks without compromising the application’s functionality.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by implementing a SHA-256 checksum to ensure data integrity, configuring HTTPS to secure data in transit, and performing static analysis with the Dependency-Check tool to identify and address vulnerabilities in dependencies. In the future, I would continue to use a combination of static analysis tools, regular code reviews, and adherence to security best practices to assess vulnerabilities. Mitigation techniques would be selected based on the severity of the vulnerabilities, industry standards, and the specific needs of the application.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure that the code and application were both functional and secure, I conducted thorough functional testing to verify that all components behaved as expected. I also ran a static analysis using the Dependency-Check tool to detect any new vulnerabilities introduced during the refactoring process. By iteratively testing and reviewing the code, I was able to confirm that the security enhancements did not compromise the functionality of the application.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The key resources and tools that were used during this project included the SHA-256 cryptographic algorithm for data integrity verification, HTTPS for secure communication, and the OWASP Dependency-Check tool for identifying vulnerabilities in third-party libraries. Secure coding practices such as encapsulation, error handling, and input validation are also important. These resources and practices will be helpful in future assignments where security is a top priority, particularly in applications that handle sensitive data or operate in regulated industries.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I would show future employers my ability to identify and mitigate software vulnerabilities, implement secure coding practices, and enhance an application’s security through cryptography and secure communications. The specific examples I would highlight include the implementation of the SHA-256 checksum, the configuration of HTTPS for secure data transmission, and the successful use of the Dependency-Check tool to manage third-party risks. These examples demonstrate my proficiency in both securing software and making dure that it remains functional and reliable.

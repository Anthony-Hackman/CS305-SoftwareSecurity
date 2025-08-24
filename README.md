# CS305-SoftwareSecurity
## Software Security 2025 C-4 (Jun - Aug)

>Choose one artifact to add to your GitHub repository for your portfolio for this course. Submit either the completed Artemis Financial Vulnerability Assessment Report or the completed Artemis Financial Practices for Secure Software Report. You created these items in Projects One and Two.

>Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that processes sensitive customer, and business data that could include personally identifiable information (PII) along with their financial information. They required data in transit to be protected end to end with transport layer security (TLS), and data at rest to be protected with an encryption or hashing.

>What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

When a security vulnerability was found, I gave which line and a snippet of the code referenced. If the vulnerability was a part of a specific dependency, I included the OWASP dependency check report and the CVE (Common Vulnerability and Exposures) identifier. The value of Software Security brings peace of mind for the stakeholders, and the clients; they will not have to worry about sensitive information being leaked or used fraudulently. The software security of a company brings a reputation as well.

>Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was analyzing the third party dependencies. Many libraries had multiple reported vulnerabilities, and it took time to determine which were relevant to the project and which were false positives. The helpful part was learning how to interpret the OWASP dependency check reports and mapping them to the codebase, which strengthened my ability to evaluate security risks in software projects.

>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by applying multiple defenses rather than relying on a single control. AES encryption with dynamic keys and IVs was used to protect sensitive data, while SHA-256 hashing ensured data integrity. Transport Layer Security (TLS) provided protection for data in transit, using secure random number generation, and structured error handling further reduced risks. In the future I will continue to use automated tools like OWASP Dependency-Check to monitor third party libraries.

>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I ensured the code was functional through running and verifying the checksums, and verified the security by running the dependency check. With every iteration of development on this project I ran the dependency check to ensure I was not adding more vulnerabilities.

>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The primary tools I used were OWASP Dependency-Check, and Eclipse with integrated security plugins. I applied secure coding practices by following Oracle’s documentation and standards, as well as avoiding hardcoded credentials. These resources and practices will be valuable in future projects, as they help maintain a balance between software functionality and security.

>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment I could show the vulnerability assessment report and the corresponding mitigation strategies. This assignment shows my ability to identify security risks, analyze and integrate secure code, and follow best practices. I  could also show both versions of the code, which shows both technical skill and an understanding of integrating secure coding principles.

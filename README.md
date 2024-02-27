# PASTA-CyberAttackTree-Lab
In this project written diagram lab, I’m conducting an analytical process to demonstrate using the PASTA framework in cyber security. This method for PASTA is process for attack simulation and threat analysis.


Stages Sneaker company
I. Define business and security objectives

Make 2-3 notes of specific business requirements that will be analyzed.

Will the app process transactions?
Does it do a lot of back-end processing?
Are there industry regulations that need to be considered?

Note: This repository highlights my individual advancements in cybersecurity subjects, drawing on content from Coursera. While the resources are sourced from Coursera, the explanations and resolutions featured here represent my personal comprehension as a cybersecurity enthusiast/professional.

Description of Sneaker Company Application:
Our platform is designed to effortlessly link sellers and shoppers. User sign-up, login, and account management are made simple and user-friendly. Data privacy is a top priority for us, aiming to instill confidence in users that we handle their information responsibly.

Buyers can easily communicate with sellers through direct messaging and have the option to rate sellers, promoting excellent service. The sales process is transparent and swift, ensuring a quick and efficient transaction. Users are provided with multiple payment options to facilitate a seamless checkout experience, with careful attention to proper payment handling to avoid legal complications.

The business application will process sales and allow for users to manage their accounts. There will be concerns about the processing of payments, ensuring it is done in an appropriate and legal fashion.
II. Define the technical scope
List of technologies used by the application for this situation:
- API
- PKI
- AES
- SHA-256
- SQL

With the utilization of SQL, it is advised to evaluate the risks of SQL injection attacks as it is the most prominent vulnerability on the list. The SHA-256 hash function is aimed at protecting user passwords and credit card information. Session hijacking is to be evaluated with the API and PKI technologies.

III. Decompose application Pasta-4.png

IV. Threat analysis
List 2 types of threats in the PASTA worksheet that are risks to the information being handled by the application.
- What are the internal threats?
- What are the external threats?

Internal threats identified will be weak login credentials. It is essential that users are subject to adequate self-imposed password security measures, such as 13 character passwords, as well as multi factor authentication.
External threats will be identified as injection attacks that the SQL database could be exposed to. The development team will need to evaluate this risk to ensure that the SQL vulnerabilities cannot be exposed.

V. Vulnerability analysis
List 2 vulnerabilities in the PASTA worksheet that could be exploited.
- Lack of prepared statements
- Weak Login Credentials

VI. Attack modeling Pasta-5.png

VII. Risk analysis and impact
List 4 security controls that you’ve learned about that can reduce risk.
- Utilizing the SHA-256 hashing method
- Principle of least privilege
- Incident response procedures
- Adequate password policies.

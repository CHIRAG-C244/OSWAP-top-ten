OWASP Top 10 Report 

A. Objective

This report's objective is to present a thorough summary of the OWASP Top 10 vulnerabilities that I investigated using the TryHackMe room. It contains all of the work I've finished and evidence of my development as I've overcome the room's obstacles. 
What  is  the OWASP Top 10 ?

The Open Web Application Security Project (OWASP) publishes a widely recognized list called the OWASP Top 10. The top ten security threats that impact web applications are highlighted. Based on feedback from organizations throughout the world, this list is updated on a regular basis to reflect the most recent developments and difficulties in application security. It is a fundamental tool for developers and security experts, with the following goals in mind:

Increase knowledge about online dangers.
Promote safe coding techniques.
Assist companies in setting priorities for their security initiatives.

Why is the OWASP Top 10 Important?

The following factors have made the OWASP Top 10 a vital resource as online applications get more intricate and cyber threats keep changing:

Setting security as a top priority aids organizations in concentrating on the biggest weaknesses.
Teaching Developers: The list offers insightful information on secure development techniques as well as helpful training resources.
Improving Security Posture: Organizations can greatly increase their overall security by fixing these vulnerabilities.


Getting Started
Task 1: Introduction

This job gives a summary of the goal and content of the TryHackMe OWASP Top 10 room.
![image](https://github.com/user-attachments/assets/969be66d-7e89-451e-a655-483c731948a4)

 

Task 2: Machine Access
directions for configuring OpenVPN and gaining access to the virtual worlds utilized for practical activities.
![image](https://github.com/user-attachments/assets/2ffc2bdc-a2e0-485e-b8b6-680ecb171ddb)



First Chapter: Injection

By delivering malicious data to an interpreter, injection attacks can fool it into carrying out unexpected commands or gaining access to data that is not authorised.

Task 3: Overview of Injection
An overview of input field exploits and SQL and NoSQL injection issues.

Task 4: Injection of OS Commands
description of how hackers use weak programs to run commands on a host operating system.

Task 5: Practical Command Injection Exercise: Take advantage of command injection flaws.  
![image](https://github.com/user-attachments/assets/9ea01d5d-7f26-48d7-88c4-0ae2388153da)




Chapter 2: Broken Authentication

Vulnerabilities in session management, password policies, and user identity verification are examples of broken authentication.

Task 6: Summary of Verification Errors
Typical problems include unsafe session management and weak passwords.

Task 7: Real-World Illustration of Authentication Vulnerabilities Practical illustration of how attackers
take advantage of these vulnerabilities 
![image](https://github.com/user-attachments/assets/53baee5d-68a7-4818-b44b-448e1660fcae)




Chapter 3: Sensitive Data Exposure.
This chapter discusses the dangers of insufficient protection for sensitive data, such as weak encryption or incorrect storage.

Task 8:  An introduction to sensitive data exposure risks, highlighting how inadequate protection measures can lead to unauthorized access to sensitive information.
Task 9: Additional resources discussing best practices for protecting sensitive data, including encryption and secure storage methods like nosql and also learnt how to extract hashes.
Task 10: Further insights into securing sensitive data against exposure through various attack vectors and learnt to crack hashes to get passwords.
Task 11:  A challenge task focused on identifying sensitive data exposure vulnerabilities within a simulated environment.
![image](https://github.com/user-attachments/assets/211721c5-1703-47b0-aae3-d35468dca317)

Chapter 4: XXE vulnerabilities occur when XML parsers analyse external entities, allowing attackers to access sensitive data or run malicious commands.

Task 12: Task Detail: Overview of XXE vulnerabilities, explaining how they occur when XML parsers process external entities within XML documents.
Task 13:  Detailed explanation of XML and its structure, along with security concerns associated with its use in applications.


 
Task 14: Understanding Document Type Definitions (DTD) in relation to XXE vulnerabilities and how they can be exploited 
![image](https://github.com/user-attachments/assets/6084976c-e49a-4759-a652-fea77f95aa14)

Task 15:  Crafting payloads specifically designed for exploiting XXE vulnerabilities in XML documents.
Task 16: Practical demonstration of exploiting XXE vulnerabilities, practicing on real-world implications of these security flaws via tryhackme machine.
![image](https://github.com/user-attachments/assets/7f16f695-2cca-42ad-a386-6e0c68251a68)

 
Chapter 5: Broken Access Control
Access control weaknesses allow unauthorised individuals to get access to restricted data or undertake privileged actions.

Tasks 17-18 provide an overview of common access control challenges.
Hands-on challenge with Insecure Direct Object References (IDORs).
![image](https://github.com/user-attachments/assets/fa03ba91-c379-4740-b432-f33b97532cd1)

 

Chapter 6: Security Misconfiguration.
Misconfigurations, such as default settings or unduly permissive permissions, might leave programs vulnerable to attacks.

Task 19: Identify prevalent misconfigurations and associated hazards.
 ![image](https://github.com/user-attachments/assets/61217d16-b1eb-476b-b555-ea2a28336d96)



Chapter 7: Cross-Site Scripting (XSS)
XSS vulnerabilities enable attackers to inject malicious scripts into web pages seen by other users.

Task 20: Learn and practise stored, reflected, and DOM-based XSS attacks.
![image](https://github.com/user-attachments/assets/ed64afc9-2765-446c-9352-9a44f70f177d)

 

Chapter 8: Insecure Deserialisation.
This vulnerability occurs when untrusted data is deserialised, which can result in denial of service or arbitrary code execution.

Tasks 21-26 provide an overview of deserialisation concerns, including cookie-based attacks.
Practical exercises for exploiting unsafe deserialisation.
![image](https://github.com/user-attachments/assets/33c812ad-4a4b-444c-9df0-a6723037caa6)
![image](https://github.com/user-attachments/assets/e491c4a1-d2bf-4e98-92d6-eccd4033ff24)
![image](https://github.com/user-attachments/assets/2099f2c0-8e2f-4d24-91c1-8ea72308aed1)
![image](https://github.com/user-attachments/assets/1ec4f173-912e-4776-aa66-1aef5dbd785c)



Chapter 9: Components With Known Vulnerabilities
The use of obsolete or vulnerable libraries and components creates major security concerns to applications.     

Tasks 27-29: Understanding the hazards.
Practical lab assignments involve detecting and utilising old components.
![image](https://github.com/user-attachments/assets/40b3367f-31c0-4292-9a86-67d6e4104846)

Chapter 10: Insufficient Logging and Monitoring.
The absence of effective recording and monitoring makes it harder to notice and respond to attacks.

Task 30: Investigate the significance of comprehensive logging and incident response procedures.
![image](https://github.com/user-attachments/assets/c5c38e65-6cf0-4850-963a-0bc90245e650)

 
E. Conclusion.
The OWASP Top 10 is an essential tool for identifying and mitigating web application vulnerabilities. Through the TryHackMe room, I acquired hands-on experience with these difficulties, which improved my practical abilities and knowledge. As a newbie, I depended on supplementary resources such as YouTube lessons and publications to help me navigate this learning process. This experience has highlighted the significance of ongoing application security education, as well as the need to be vigilant against evolving threats.

.
The OWASP Top 10 is an essential tool for identifying and mitigating web application vulnerabilities. Through the TryHackMe room, I acquired hands-on experience with these difficulties, which improved my practical abilities and knowledge. As a newbie, I depended on supplementary resources such as YouTube lessons and publications to help me navigate this learning process. This experience has highlighted the significance of ongoing application security education, as well as the need to be vigilant against evolving threats.

MY room completion BADGE:
![image](https://github.com/user-attachments/assets/596e5387-c501-4dc4-86cf-4cff3686bd22)




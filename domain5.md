# Identity and Access Management

## Elevator pitch
This domain foucuses on communications over the network as obviously stated. Less obviously stated, this domain dives into the how and what with these communications are done. Are you going to have to know all 65536 TCP and UDP ports? Probably not. Are you going to need to distinguish protocols or technology used in each layer? More than likely.

## Topics

## Type 1 Authentication: Something you know
### Passwords
- Static passwords: 
- Dynamic Passowrds: 
- One-time passwords: 
- Passphrases: 
- Salts: A random value added to a password prior to hashing, which will encrypt differently.

### Password Attacks
- Dictionary: A word list, e.g. rockyou.txt
- Hybrid Attack: appends, prepends or changes characters in words from a dictionary before hashing
- Brute Force: calculates hash outputs for every possible password
- Rainbow Tables: a database that contains the precomputed hashed output for most or all passwords

## Type 2 Authentication: Something you have
- Synchronous dynamic token
- Asynchronoous dynamic token

## Type 3 Authentication: Something you are
### Biometric Systems and Accuracy
- False Acceptance Rate (FAR): unauthorized subjects are accepted as valid
- False Rejection Rate (FRR): authorized subjects are rejected.
- Crossover Error Rate (CER): the point where FAR and FRR are equal. This describes the overall accuracy of the system

## Access Control models
- Rule-Based: Much broader scenarios than individual subjects accessing objects e.g. a Firewall
– RBAC: Role Based Access Control. Defined rules or restrictions for accesing objects in a system
- DAC: Users have direct control over all programs and files
- MAC: Opposite of DAC. Using a policy or Hardware/Software component to restrict access

## Identity Managemnet
- Federated Identity Management: applies SSO at a wider scale ranging from cross-organiztional to Internet scale.
- SAML: An XML based framework for exchanging security information
- LDAP: A common open protocol for interfacing and querying directory service informaiton provided by network operating systems.
- Kerberos: Authentication service used to support SSO using symmetric encryption providing mutual authentication of clients and servers

## Kerberos Components
- Principal: Client (user) or service
- Realm: A logical Kerberos network
- ticket: Data authenticating a principal's identity
- Credentials: A ticket and service key
- KDC: Key Distribution Center, authenticates principles
- TGS: Ticket Granting Service
- TGT: Ticket Granting Ticket
- C/S: Client Server, regarding communications between the two


![Kerberos Steps](https://phoenixnap.com/blog/wp-content/uploads/2020/09/how-kerber-works.png)


## AAA (Auentication, Authorization, Accounting)
- It refers to five elements: Identification, authentication, authorization, auditing, and accounting.
- Authentication: The process of verifyhing or testing the identity claimed by a subject is valid.
- Authorization: The process ensuring the subject accessing the object has the necessary rights and privileges.
- Accounting: The process of holding someone responsible for something. Accoutability is possible if a subject's identity and actions can be tracked and verified.

## Access Control Protocols
- RADIUS: Remote Authentication Dial In User Servcie. An AAA system comuunicating over UDP (ports 1812, 1813).
- Diameter: A successor to RADIUS
- TACACS/TACACS+: Terminal access controller access control system. A centralized access control system requiring users to sen4d and ID and static password for authentication. TACACS+ allows for two-factor strong authentication. Uses UDP (port 49). TACACS+ uses TCP (port 49)
- PAP/CHAP: PAP (Password Authentication Protocol) is insecure as passwords are sent in clear text. CHAP (Challenge Handshake Authentication Protocol). Provides protection against playback attacks.


## Useful Links

- [Back to the YouTube Video]()
- [Bypassing Biometric Controls](https://www.youtube.com/watch?v=ANllOmgJH9Y)
- [Kerberos Deep Dive](https://www.youtube.com/watch?v=5N242XcKAsM)
- [Kerberos steps explained better](https://www.vanimpe.eu/2017/05/26/kerberos-made-easy/)
- [Password Lists](https://github.com/danielmiessler/SecLists/tree/master/Passwords)
- [TryhackMe - Attacking Active Directory](https://tryhackme.com/room/attacktivedirectory)
- [Darnet Diaries Episode 33 - Rockyou](https://darknetdiaries.com/episode/33/)
- [BloodHound](https://www.sans.org/blog/bloodhound-sniffing-out-path-through-windows-domains/)
- [Inside Cloud and Security - Domain 5](https://youtu.be/o-jeH8OlKfs)
- [Rule Based vs Role Based Access Control](https://blogs.iuvotech.com/rbac-rule-based-vs.-role-based-access-control)
- [Plan for Kerberos Authentication](https://docs.microsoft.com/en-us/sharepoint/security-for-sharepoint-server/kerberos-authentication-planning)


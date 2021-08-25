# Identity and Access Management

## Elevator pitch
This domain foucuses on communications over the network as obviously stated. Less obviously stated, this domain dives into the how and what with these communications are done. Are you going to have to know all 65536 TCP and UDP ports? Probably not. Are you going to need to distinguish protocols or technology used in each layer? More than likely.

## Topics

# Type 1 Authentication: Something you know
### Passwords
- Static passwords
- Dynamic Passowrds
- One-time passwords
- Passphrases
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
- Crossover Error Rate (CER): the point where FAR and FRR are equal. This describes the overall accuracy of the sy

## Access Control models
- Rule-Based: 
– RAC: Role Based Access Control. Defined rules or restrictions for accesing objects in a system 
- DAC: Users have direct control over all programs and files
- MAC: Opposite of DAC. Using a policy or Hardware/Software component to restrict access

## Identity Managemnet
- SAML
- LDAP
- Kerberos

## More Kerberos related things
- Principal:
- Realm:
- ticket: 
- Credentials
- KDG
- TGS
- TGT
- C/S

## Access Control Protocols
- RADIUS
- Diameter
- TACACS/TACACS+
- PAP/CHAP
- 

## Useful Links

- [Back to the YouTube Video]()
- [Bypassing Biometric Controls](https://www.youtube.com/watch?v=ANllOmgJH9Y)
- [Kerberos Deep Dive](https://www.youtube.com/watch?v=5N242XcKAsM)
- [Password Lists](https://github.com/danielmiessler/SecLists/tree/master/Passwords)
- [TryhackMe - Attacking Active Directory](https://tryhackme.com/room/attacktivedirectory)
- [Darnet Diaries Episode 33 - Rockyou](https://darknetdiaries.com/episode/33/)
- [BloodHound](https://www.sans.org/blog/bloodhound-sniffing-out-path-through-windows-domains/)
- [Inside Cloud and Security - Domain 5](https://youtu.be/o-jeH8OlKfs)


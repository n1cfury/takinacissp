# <p align=center>Domain 7 - Security Operations</p>

## Elevator Pitch
This is where the rubber meets the road and the practice of protecting an organization and responding to threats comes into play. A lot of operational concepts covered such as what you're protecting and how in addition to responding to events and incidents. Most of the tools used by a defensive centric (Blue Team) role will be covered in this domain.

## Administrative Security
- Least Privilege: Granting people the bare minimal access needed to complete 
- Separation of Duties: Ensuring individual duties are assigned rather than one person having all the keys to the castle
- Job Rotation: Rotation of responsibilities to help mitigate the risks of any one individual having too many privileges. 
- Nondisclosure agreement (NDA): A work related contractural agreement ensuring an individual maintains confidentiality prior to access of sensitve information.

## Monitoring Actiivty
- Event: Any observable activity in your IT infrastructure
- Alert: A notification of an event
- Incident: An event that negatively affects the IT Infrastructure

## Incident Response steps
- Preparation: Determining what to do or know before an incident.
- Detection (Identifcation): You've identifed an Alert for an event, and confirmed it is an incident.
- Response (Containment): Now that you're responding, you need to stop the bleeding
- Mitigation (Eradication): You've contained the damage from the incident, now to eliminate the threat.
- Reporting: You've eliminated the threat, what were your findings?
- Recovery: You've provided a report after responding. Now to get back to the state prior to the incident. 
- Lessons Learned: Situation is back to normal, what did you learn? What could you have done better?

![Incident Response Steps](https://cdn-cybersecurity.att.com/blog-content/incident-response-steps-comparison-guide-framework-side-by-side.jpg)

## Indicators of Compromise (just a few...some of these may require further investigation)
- Suspicious network traffic
- Unusual applications
- Unusual behavior from accounts (privileged or otherwise)
- Suspicious authentication

## Asset Management
- Vulnerability Management: Reducing the attack surface
- Baselining: Gold images come to mind.

## RAID
- RAID 0: Striped set
- RAID 1: Mirroed set
- RAID 2: Hamming code. Cost prohibitive, requiring 14-39 disks
- RAID 3: Byte level striping with dedicated parity
- RAID 4: Block level striping with dedicated parity
- RAID 5: Block-level striping with distributed parity
- RAID 6: Block-level striping with double-distributed parity
- RAID 1+0/10: Multi-raid

## Business Continuity Plan/Disaster Recovery Plan
- Hot Site: A backup facility maintained in constant working order. Allows for the fastest continuation during a disaster.
- Warm Site: The middle ground backup facility. Equipment may be available, but may not include current copies of data.
- Cold Site: Standby facility with appropriate electrical and support systems. Slowest continuation during a disaster.

### Disaster Recovery Process
 - Respond
 - Activate Team
 - Communicate
 - Assess
 - Reconstitution

## Backups
- Full: A complete copy of data containedon the protected device on the backup media. This also refers to the process of making a complete copy of the data.
- Incremental: A backup that storing only those files that have been modifed since the time of the most recent full or incremental backup. 
- Differential: A backup that stores all files that have been modified since the time of the most recent full backup

## Failure and Recovery Metrics
- MTTF (Mean Time To Failure): Length of time or number of uses a hardware or media component can endure before its reliability is questionable.
- RTO (Recovery Time Objective): The maximum time a business can be inoperable without causing ireparable harm.
- RPO (Recovery Point Objective): The maximum amount of data loss without causing irepparable harm.

## Useful Links
- [Back to the YouTube Video]()
- [Inside Cloud and Security - Domain 7](https://www.youtube.com/watch?v=Vle4g2apsvc)
- [Events, Alerts, and Incidents](https://danielmiessler.com/study/event-alert-incident/)
- [Incident Response Book](https://www.amazon.com/Incident-Response-Computer-Forensics-Third/dp/0071798684/ref=asc_df_0071798684/?tag=hyprod-20&linkCode=df0&hvadid=312091457223&hvpos=&hvnetw=g&hvrand=7510202046434899008&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031327&hvtargid=pla-464897074962&psc=1&tag=&ref=&adgrpid=62820903995&hvpone=&hvptwo=&hvadid=312091457223&hvpos=&hvnetw=g&hvrand=7510202046434899008&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031327&hvtargid=pla-464897074962)
- [Indicators of Compromise](https://www.crowdstrike.com/cybersecurity-101/indicators-of-compromise/)
- [NIST SP800-34 - Contingency Planning Guide for Federal Systems](https://csrc.nist.gov/publications/detail/sp/800-34/rev-1/final)
- [Blue Team Labs](https://blueteamlabs.online/)
- [Differential vs Incremental Backups](https://www.acronis.com/en-us/articles/incremental-differential-backups/#:~:text=A%20differential%20backup%20backs%20up,since%20the%20last%20full%20back.&text=Incremental%20backups%20also%20back%20up,a%20full%20or%20incremental%20backup.)
- [Recovery Point and Recovery Time Objective](https://dbvisit.com/understanding-rto-and-rpo-disaster-recovery)
- [Incident Response Steps](https://cybersecurity.att.com/blogs/security-essentials/incident-response-steps-comparison-guide)
- [Blue Team Blog - IDS/IPS tools](https://blueteamblog.com/ips-vs-ids-an-overview)

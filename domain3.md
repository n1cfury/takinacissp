### Security Architecture and Engineering

## Elevator pitch: 
Biggest and most technical of the eight domains. This one focuses on security at the architectural level. Think big picture here to the point of designing the best ways to ensure a secure system...reducing risk from disasters as well.


# Topics

## Security Models
- Bell La Padula (DoD): No read up, No write down. An emphasis on (Confidentiality focused model).
- Clark Wilson: Requires subjects to access objects via programs. Separation of duties.
- Biba: No read down, No write up (Integrity focused model).
- Brewer & Nash (Chinese Wall): Avoids conflicts of interest, prohibits access to multile objects by a subject.

## Cryptography
- Asymmectric Encryption (stronger, but slower), uses public and private keys
- Symmetric Encryption (weaker but faster), uses shared secret keys

## Malware
- Macro Virus: Focused on standard office related applications (Think MSFT Office apps with macros e.g. Word, Excel)
- Boot Sector Viruses: Infects at the boot sector
- Stealth Virus: Designed to hide from the OS and antiviruses
- Polymorphic Viruses: Changes signatures in an effort to avoid detection
- Multipartie Viruses: Speads via multiple vectors

## Protection Rings
- Ring 0: System (privileged mode)
- Ring 1: Various OS Components
- Ring 2: Device Drivers
- Ring 3: Application/User space (least trusted)
- ![Protection Ring](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Priv_rings.svg/600px-Priv_rings.svg.png)

## Other Topics
- Layering: Separates hardware and software fuctionality into modular tiers
- Abstraction: hides unnecessary details from users
- Multitasking: Allows multiple tasks to run on a single CPU
- Multithreading: 
- Multiprocessing: Allows multiple processes on multiple CPUs


### DES Summary: Uses 64 bit block sides with five modes
** Block
- ECB (Electronic Code Block): Weakest form of DES. No initialzation vector. Plaintext
- CBC (Cipher Block Changing): blcok modes uses XORs of DES. Encryption errors will propogae

** Stream
- CFB (Cipher Feedback): 
- OFB (Output Feedback): Uses subkey before being XORed
- CTR (Counter Mode): Uses a counter for feedback. No error propagation

## Logical Operations (remember the symbols)
![Logical Operations](https://www.researchgate.net/profile/Shaveta-Thakral/publication/307084597/figure/tbl2/AS:667033544978441@1536044598645/Function-Table-for-Logical-Operations.png)

- NOT 
- AND
- OR
- XOR

## Safety First
### Clases of Fires
- Class A: Conbustibles. Treatable with water/soda acid
- Class B: Liquid. Treatable with Halon/CO2
- Class C: Electircal. Treatable with Halon/CO2
- Class D: Metals. Treatable with Dry Powder

### Fire Suppresion Systems
- Wet Pipe: Contains water that discharges immediately when triggered aka closed head system
- Dry Pipe: Contains compressed air. Once triggered, air escapes, which opens a water valve, then discharges water
- Deluge: Another form of dry pipe that uses larger pipes, thus a lot more water. Probably not good for environments containing electronics.
- Preaction: A combination of dry/wet pipe. Water is released once sprinkler head activation triggers are melted by sufficient heat. Most appropriate for environments with computers and humans.

## Useful Links

- [Back to the YouTube Video](https://youtu.be/Y343SeisDxg)
- [Inside Cloud and Security - Domain 3](https://www.youtube.com/watch?v=iEBHjVcu_8s&list=PL7XJSuT7Dq_XPK_qmYMqfiBjbtHJRWigD&index=14)
- [Serious Cryptography](https://nostarch.com/seriouscrypto)
- [Cryptography - Coursera](https://www.coursera.org/learn/crypto)
- [Bitwise Operation](https://en.wikipedia.org/wiki/Bitwise_operation)

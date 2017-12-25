# Notes

## Cryptography Engineering - ISBN:978-0470-47424-2

Scratch Notes
- Cryptography is both easy and difficult
- Role of cryptography in Systems
  - Lock
  - Big Picture
  - Useless on its own
  - Walls and fences
- importance of security on rest of the system
- Weakest link property
- Signs of Breakage in a system
  - Breaking the cryptography of a system vs breaking remaining pieces of a system
- Designing attack trees
- Defence in depth
  - Attacker's perspective of weakest link
  - Attacker's objective
- Adversarial Setting
- Professional Paranioa
  - Attacker's motive is unknown
- Standards of cryptography community
  - Attack the system and not the person
  - Try breaking a new system to look for faults
  - Do not invent your own cryptographic method and if you do, get it peer reviewed
  - Constructive critism
- Trade offs
- Relative threat analysis of security model
- Cryptography is not always the only solution
- Generic Attacks outside the cryptosystem
  - Define
  - Provide analysis
  - No cryptosystem is completely resistant to generic attacks
- Defining priorities while designing the system:
  - That works, is safe and secure
  - Efficient 
  - Willing to spend 90% of resources to keep system secure always. 
  - Not always necessary or need but willing to expend such resources if needed.
  - if given an option to use 90% of resources to main security and lesser features or use lesser resources for a less secure system, always choose with secuirty being the highest and paramount priority.
  - Security comes first, second and third along priority scale; after that comes performance and effeciency
  - under no ciircumstance will you compromise on security
- Security vs Features
  - Simplicity is always better than complexity
  - Complexity is a measure of how many things interact at one point
  - Build modular structures
  - Complexity is the worst enemy of security
  - System needs to be built from ground up with security in mind
- Security vs evolving systems
  - Needs to withstand the test of time
  - designers must account for evolving systems and continuous development and incoming/expected attacks
  
- Excercises
  - For professional paranoia
    - immersion
    - Acceptance
  - Analysis of current events
  - Security review excercises [PG 20]
  - General Excercises
  
  ***
  
- What is encryption
  - example Alice -- Eve -- Bob
- Kerckhoff'S principle
- Public key encryption
  - Eg: communication with large number of entities involved
  - ![Circular depiction of 20 people trying to communicate using different keys for each](https://img.buzzfeed.com/buzzfeed-static/static/2015-01/21/3/enhanced/webdr06/enhanced-buzz-4802-1421830346-4.jpg)
- Digital Signatures
- Public Key Infrastructure(PKI)
  - Central authority: Certificate Authority

***

Attacks:

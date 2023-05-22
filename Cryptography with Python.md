# Cryptography with Python


## Cryptography & Its classic security goals.

### Cryptology
    General subject for the study of systems allowing for secure communication which involves 
    both the constructive side with Cryptography and analytical side with Cryptanalysis.
    - Cryptography
        Subject that deals with construction of systems that allow for secure communication or writing.
    - Cryptanalysis
        Subject that analyses those systems constructed by cryptography in terms of their strength or security.

### Classic goals of Information Security (CIA)
    - Confidentiality (C)
        Information is only accessible to an authorized party.
    - Integrity (I)
        Correctness and completeness of information can be verified.
    - Availability (A)
        Information is available when needed.
        *This security goal is out of reach for cryptograhpy because cryptography is abstract subject very close to mathematics.
        The ideas of cryptography are coded up into cryptographic primitives such as encryption, these cryptographic primitives 
        are then made use of in technical protocols such as TLS (Transport Layer Security) protocols and these technical protocols
        then make up the technical systems that ultimately run on physical machines. From this, it can be seen that if information
        in an information technology system needs to be available, then this is mostly the responsibilty of an outer layer, with 
        cryptography residing towards the more inner core of the system.*

### Classic goals of Cryptography
    - Confidentiality
        Information is only accessible to an authorized party.
    - Integrity
        Correctness and completeness of information can be verified.
    - Authenticity
        Source of information can be verified by a receiving party.
    - Non-Repudiation
        Source of information can be verified by any third party.
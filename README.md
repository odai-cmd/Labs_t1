1. What is Cybersecurity? (CIA Triad)

Cybersecurity refers to the methods, technologies, and practices used to protect computers, networks, applications, and data from unauthorized access, attacks, damage, or disruption.

The foundation of cybersecurity is based on three key principles, collectively known as the CIA Triad:

Confidentiality

Integrity

Availability

a) Confidentiality

Confidentiality ensures that sensitive information is accessible only to authorized users and is protected from unauthorized disclosure.

Real-world examples:

Banking systems: Personal and financial data (account numbers, balances, transaction history) are protected using passwords, PINs, encryption, and multi-factor authentication.

Social media and messaging apps: Applications like WhatsApp use end-to-end encryption so that only the sender and receiver can read messages.

Impact if compromised:

Identity theft

Financial loss

Exposure of business secrets

b) Integrity

Integrity ensures that data remains accurate, complete, and trustworthy throughout its lifecycle and is not modified without proper authorization.

Real-world examples:

Online banking transactions: The amount sent by a user must remain unchanged during processing.

Healthcare records: Patient data must remain accurate to prevent medical errors.

Impact if compromised:

Incorrect or corrupted data

Fraud and legal consequences

Loss of trust in systems

c) Availability

Availability ensures that systems, services, and data are accessible to authorized users whenever needed.

Real-world examples:

E-commerce platforms: Must remain available during peak shopping periods.

Cloud services: Businesses depend on continuous access to cloud applications and data.

Threats to availability include:

Distributed Denial of Service (DDoS) attacks

Hardware failures

System misconfigurations

2. Types of Attackers

Cyber attackers vary in skill level, resources, and motivation. Understanding attacker types helps organizations design effective defenses.

Script Kiddies
Individuals with limited technical skills who use pre-made tools or scripts. They typically attack easy targets for fun, curiosity, or recognition.

Insiders
Employees, contractors, or partners with legitimate access. Threats may be intentional (data theft) or unintentional (accidental data leaks).

Hacktivists
Attackers motivated by political, social, or ideological beliefs. Common activities include website defacement, data leaks, and denial-of-service attacks.

Nation-State Actors
Highly advanced attackers backed by governments. They conduct cyber espionage and attacks on critical infrastructure such as power grids, banking systems, and defense networks.

3. Common Attack Surfaces

An attack surface consists of all possible entry points an attacker can use to compromise a system.

Common attack surfaces include:

Web applications (login pages, forms, admin panels)

Mobile applications (insecure storage, weak permissions, vulnerable APIs)

APIs (poor authentication, exposed endpoints)

Networks (public Wi-Fi, routers, firewalls, open ports)

Cloud infrastructure (misconfigured storage, exposed services, weak access controls)

Reducing the attack surface lowers overall security risk.

4. OWASP Top 10 Vulnerabilities (Overview)

The OWASP Top 10 identifies the most critical security risks to web applications.

Key vulnerabilities include:

Broken Access Control: Users can access data or perform actions beyond their authorization.

Injection Attacks: Malicious inputs (e.g., SQL injection) manipulate backend systems.

Authentication Failures: Weak passwords, poor session handling, or missing multi-factor authentication.

Security Misconfiguration: Default credentials, unnecessary services, or exposed error messages.

Sensitive Data Exposure: Failure to encrypt data in storage or during transmission.

These vulnerabilities allow attackers to steal data, gain system control, or disrupt services.

5. Mapping Daily-Used Applications to Attack Surfaces
Application	Possible Attack Surfaces
Email	Phishing emails, malicious attachments, fake login pages
WhatsApp	Account takeover, social engineering, SIM swapping
Banking Apps	Insecure APIs, weak authentication, malware on devices
Social Media	Credential stuffing, fake profiles, malicious links
6. Data Flow: User → Application → Server → Database

A typical application data flow includes:

User: Enters data (login credentials, messages, payment information)

Application: Processes input and sends a request

Server: Validates requests, applies business logic, and checks permissions

Database: Stores, updates, or retrieves data

Response: Data is returned to the application and displayed to the user

Understanding this flow helps identify where security controls should be implemented.

7. Where Attacks Can Occur During the Data Flow

User level: Phishing, weak passwords, malware-infected devices

Application level: Input validation flaws, broken authentication, insecure sessions

Server level: Unpatched software, exposed services, misconfigurations

Database level: SQL injection, excessive privileges, data leaks

Data in transit: Man-in-the-middle attacks when encryption is missing

Effective security requires protection at every stage.

8. Summary (In My Own Words)

Cybersecurity focuses on protecting systems and data by maintaining confidentiality, integrity, and availability. Attackers range from inexperienced individuals to highly sophisticated nation-state actors, each exploiting different attack surfaces.

Modern applications expose multiple potential vulnerabilities, making security a critical requirement. By understanding common threats, the OWASP Top 10 vulnerabilities, and how data flows through applications, organizations can identify weak points and apply appropriate security controls to reduce risks and protect users.

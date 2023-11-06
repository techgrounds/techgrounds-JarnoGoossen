# [IAM]
[Geef een korte beschrijving van het onderwerp]

## Key-terms

- authentication - Allow or denny access to resources
- authorization - Prove you are who you claim you are
- IAM - Identity Access Management
- Multi-factor authentication (MFA)

## Opdracht

- The difference between authentication and authorization.
- The three factors of authentication and how MFA improves security.
- What the principle of least privilege is and how it improves security.
### Gebruikte bronnen
[Plaats hier de bronnen die je hebt gebruikt.]

### Ervaren problemen
[Geef een korte beschrijving van de problemen waar je tegenaan bent gelopen met je gevonden oplossing.]

### Resultaat

**Authentication:**

Authentication is the process of verifying the identity of a user, system, or entity trying to access a particular resource or system. It answers the question, "Who are you?" Authentication ensures that the user or entity is who they claim to be before granting access. Common methods of authentication include:

a. Username and password: Users provide a unique username and a secret password to prove their identity.
b. Biometrics: This includes fingerprint scanning, facial recognition, or retina scanning to authenticate based on unique physical characteristics.
c. Smart cards: Users present a physical card containing a microchip or magnetic stripe that stores authentication information.
d. Two-factor authentication (2FA) or multi-factor authentication (MFA): These methods combine multiple authentication factors, such as something you know (password), something you have (smartphone), or something you are (fingerprint) to enhance security.

Authentication is the first step in the access control process and ensures that only authorized users gain entry.

**Authorization:**

Authorization, on the other hand, is the process of determining what actions or resources an authenticated user or system is allowed to access or perform. It answers the question, "What are you allowed to do?" Authorization defines the permissions and privileges granted to authenticated users, specifying what they can or cannot do within a system or application. This process is often based on roles, groups, or specific permissions associated with a user's account. Examples of authorization include:

a. Role-based access control (RBAC): Users are assigned specific roles, and each role has predefined permissions. Users inherit the permissions associated with their assigned roles.
b. Access control lists (ACLs): Individual resources or objects have associated lists that specify which users or groups are allowed to access them and what type of access they are granted (read, write, delete, etc.).
c. Attribute-based access control (ABAC): Access decisions are based on various attributes, such as user attributes, resource attributes, and environmental attributes.

In summary, authentication verifies the identity of a user or system, while authorization controls what that authenticated entity can do or access. Both authentication and authorization are critical components of access control mechanisms and work together to ensure the security and integrity of systems and data.

#### Authentication can be enhanced through the use of multiple factors, which provides an extra layer of security by requiring users to provide more than one type of authentication. The three common factors of authentication are:

- Something you know: 

This factor is based on information that only the user should know. It typically includes a secret, such as a password, a personal identification number (PIN), or answers to security questions. This factor relies on the user's ability to recall and provide the correct information during the authentication process.

- Something you have: 

This factor is based on possession of a physical object or device that only the user should have. Examples include a smartphone, a smart card, a hardware token, or an authentication app. To complete the authentication, the user must possess the physical item and use it as part of the authentication process.

- Something you are: 

This factor relies on biometric characteristics that are unique to an individual. Biometric authentication methods include fingerprint recognition, facial recognition, iris scanning, voice recognition, and other physical or behavioral traits. These traits are difficult to replicate and are often used for secure authentication.

## how MFA enhances security:

- Increased Security: 

MFA makes it significantly more challenging for unauthorized individuals to gain access because they need to possess multiple authentication factors. Even if a malicious actor manages to obtain one factor (e.g., a stolen password), they would still need the other factor(s) to complete the authentication process.

- Reduces the Impact of Credential Theft: 

In cases where passwords or PINs are stolen or compromised, MFA acts as a secondary line of defense. Even if an attacker has the "something you know" factor, they would still need the "something you have" (e.g., a smartphone app) or "something you are" (e.g., a fingerprint) to gain access.

- Mitigates Phishing Attacks: 

MFA helps protect against phishing attacks where attackers try to trick users into revealing their credentials. Even if a user is tricked into disclosing their password, MFA adds an extra layer of protection by requiring a second factor that the attacker typically doesn't have.

- Compliance and Regulatory Requirements:

 Many industries and organizations are required to implement MFA as part of their security and compliance efforts. MFA helps meet various security standards and regulatory requirements.

- User-Friendly: 

MFA can be implemented in a user-friendly way, such as through mobile apps, making it convenient for users while enhancing security.


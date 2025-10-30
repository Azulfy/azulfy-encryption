# azulfy-encryption

Overview:
The Azulfy Encryption System is a privacy-preserving technology designed to securely handle user location data and enable computations on encrypted information. It is based on homomorphic encryption, specifically inspired by ESA Patent EP 3 671 281 A1, allowing data processing without exposing raw user information.

Core Components and Functionality:

User Location Encryption – Encrypts GNSS coordinates using a homomorphic scheme, ensuring user privacy.

Encrypted Distance Computation – Computes distances between encrypted locations directly in the encrypted domain, without needing access to plaintext coordinates.

Decryption of Results – Decrypts the computed distance using an authorized key, enabling meaningful outputs while maintaining confidentiality of underlying data.

Technical Achievements:

Developed three integrated APIs, each linked to a microservice in the cloud, enabling a full end-to-end encrypted workflow.

Successfully implemented multiplicative and subtractive homomorphic operations, enabling practical distance calculations.

Tested and validated the system internally, ensuring robustness and correctness.

Applications:

Municipalities can alert users about environmental hazards, such as proximity to polluted areas, without accessing their actual locations.

Integration into space-based products and pilot services, demonstrating secure location-based applications.

Recognized as a finalist in the MEO Challenge and validated through real-world use cases.

Achievements and Recognition:

Engagement with the ESA patent author, enabling technical guidance and validation.

Applied in competitions and hackathons: the system contributed to a post-quantum crypto solution winning the EU Space Cybersecurity Hackathon.

Laid the foundation for future deployments in privacy-preserving GNSS and space applications.

Impact:
The Azulfy Encryption System represents a practical and scalable solution for secure, privacy-conscious location services, demonstrating the feasibility of homomorphic encryption in real-world space and municipal applications.

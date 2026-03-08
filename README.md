Void the Hack: Decentralized AI Cyber Range

**Void the Hack** is an on-premise, AI-augmented platform designed to provide a secure environment for cybersecurity education and research. It bridges the "Expert Gap" by integrating a context-aware Large Language Model (LLM) directly into a containerized laboratory environment.

---

### 🏗️ Core Architecture

- **Intelligence Layer ("Void"):** A gRPC-based microservice hosting a specialized LLM optimized for low-level systems programming, including Assembly, C, and C++.
    
- **Control Plane:** A Java-based API Gateway that acts as the central nervous system, managing authentication, session persistence, and command routing.
    
- **Lab Manager:** Interfaces with Docker to provision ephemeral, stateless container environments for specific research modules.
    
- **Security Mesh:** A Software Defined Perimeter (SDP) utilizing Headscale and WireGuard to create a zero-trust network between the engine and student nodes.
    

### ⛓️ Blockchain-Based Anonymous Auth

- **Decentralized Identity:** Utilizing a P2P blockchain layer for secure authentication and immutable verification of professional certificates and badges.
    
- **Data Sovereignty:** All sensitive research and PII remain within the localized mesh, enforced by the decentralized architecture.
    
- **Traffic Isolation:** Virtual Private Clouds (VPC) per user ensure that live exploits or malware remain contained within the lab.
    

### 🛠️ Technical Arsenal

- **Languages:** Java (System Architecture), Bash, Python, and x86-64 CPU Architecture fundamentals.
    
- **Infrastructure:** Docker, Docker-Compose, Debian Linux, and Kasm Workspaces.
    
- **Security Tooling:** Nmap, Wireshark, Burp Suite, and Metasploit.
    
- **Deployment:** A single-binary Java installer bootstraps the entire ecosystem for a "Zero-Config" user experience.

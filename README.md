# AceHack 4.0: Decentralized Identity & Reputation System
# WEB-3 SLCM

## Overview -  Web3 Domain Name Service (DNS) for MUJ Students

In today's rapidly evolving digital landscape, the future of documents, certificates, and credentials lies in blockchain technology. By storing them as Non-Fungible Tokens (NFTs), institutions can ensure security, immutability, and verifiable authenticity in a trustless and decentralized manner. This paradigm shift is set to revolutionize how academic and professional credentials are managed.

However, the traditional Web2-based university student email systems fall short when it comes to securely receiving, storing, and proving the authenticity of NFT-based documents.

To bridge this gap, we propose the development of a Web3 Domain Name Service (DNS) for Manipal University Jaipur (MUJ) students. This innovative platform will equip students with Web3-compatible domains under the university’s domain name, empowering them to securely receive, manage, and verify their NFT credentials.

Additionally, the portal is the web3 implementation of our portal: [mujslcm.jaipur.manipal.edu](https://mujslcm.jaipur.manipal.edu). This platform not only enables Web3 domain management but also tracks student attendance, certificates, and other essential academic credentials, providing an all-in-one solution for students and faculty.

---

## Problem Statement
## Decentralized Identity & Reputation System

Traditional systems for identity verification and credential management suffer from:

1. Centralized control leading to single points of failure

2. Lengthy manual verification processes

3. Vulnerability to fraud and tampering

4. Limited portability across platforms

5. Lack of standardized reputation metrics

---

## Objectives

1. Enable Secure Document Management  
   Provide students with Web3 domains to securely receive, store, and manage NFT-based documents, certificates, and credentials.

2. Ensure Verifiable Authenticity  
   Facilitate a trustless verification process for academic and professional credentials, ensuring immutability and tamper-proof authenticity.

3. Enhance Digital Identity  
   Empower students with a decentralized digital identity, fully integrated with blockchain technology, putting them in control of their academic records.

4. Streamline Credential Verification  
   Simplify the credential verification process for employers and institutions, reducing manual intervention and delays.

5. Integrated Attendance and Certificate Management  
   Enable students to track their attendance and receive blockchain-verified certificates directly through the portal, creating a unified platform for academic and credential management.

---

## Key Features

### 1. Web3 Domain Registration

- Students will be able to register unique Web3 domains (e.g., `studentname.muj`) under the MUJ domain.
- These domains will serve as decentralized digital identities, enabling secure interactions with blockchain-based services.

### 2. NFT Document Integration

- The platform will facilitate the receipt and storage of NFT-based documents on the blockchain.
- Credentials will be stored securely, ensuring easy access and long-term retention.

### 3. Trustless Verification

- Leveraging blockchain technology, third parties can verify the authenticity of documents without intermediaries.
- This ensures a seamless and tamper-proof verification process for employers and other stakeholders.

### 4. Attendance and Certificate Tracking

- Integrate with the university’s student lifecycle management system to allow students to monitor attendance records.
- Issue attendance reports and certificates as NFTs for enhanced security and verifiability.

### 5. User-Friendly Interface

- A simple and intuitive dashboard will allow students to manage their Web3 domains, NFT documents, attendance, and verification requests.
- Mobile-friendly and optimized for accessibility, the interface will make adoption seamless for all users.

---

## Impact

The Web3 Domain Name Service will place MUJ at the forefront of the digital transformation in higher education. By integrating blockchain technology, MUJ will:

- Empower Students: Provide them with cutting-edge tools to manage their academic and professional credentials securely.
- Enhance Credibility: Position itself as a pioneer in the adoption of decentralized technologies for academic records.
- Streamline Verification: Reduce the time and cost associated with credential verification processes for employers and institutions.
- Set Global Standards: Establish MUJ as a leader in blockchain-driven innovation for educational institutions worldwide.

This initiative will not only provide immediate benefits to current students but will also serve as a model for the future of credential management in higher education.

---

## Conclusion

The Web3 Domain Name Service for MUJ students is a visionary project that aligns with the future of digital credentials. By providing a secure, decentralized, and verifiable platform for managing NFT-based academic records, MUJ will empower its students and enhance their digital identity. This transformative initiative will set a precedent for universities globally, leading the way toward a blockchain-enabled educational ecosystem.

---

## Local Setup Instructions

### Backend Setup
Follow these steps to set up the backend:

1. Clone the repository:
   ```bash
   git clone https://github.com/addiiiti/AceHack-Aptos-project.git
   ```

2. Navigate to the backend folder:
   ```bash
   cd AceHack-Aptos-project/backend
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Compile smart contracts:
   ```bash
   npx hardhat compile
   ```

5. Deploy contracts to testnet:
   ```bash
   npx hardhat run scripts/deployGreeter.ts --network aptos-testnet
   ```

---

### Frontend Setup
Follow these steps to set up the frontend:

1. Navigate to the frontend folder:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Access the app at [http://localhost:3000](http://localhost:3000).

---

## Team Members

1. **Vaibhav Mittal**: Full-stack Developer & Blockchain Developer 
2. **Aditi Kumiri**: UI/UX Designer & Frontend Developer  

---

## Impact

Our project aims to redefine identity management by providing users with decentralized tools that ensure security, transparency, and efficiency:
- **Empowering Users**: Ownership of credentials and reputation metrics.
- **Streamlining Verification**: Reducing manual intervention in credential validation processes.
- **Enhancing Credibility**: Transparent scoring mechanisms visible to employers or institutions.
- **Driving Innovation**: Introducing blockchain-based solutions in academic environments.

---

## Future Roadmap

1. Expand reputation scoring algorithms to include additional metrics (e.g., academic achievements).
2. Develop mobile applications for on-the-go credential management.
3. Integrate cross-chain support for interoperability across multiple blockchains.
4. Launch a marketplace for skill endorsements and peer recommendations.

---

*Developed during AceHack 4.0 at UEM Jaipur (March 29–30th, 2025).*

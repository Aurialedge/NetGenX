NetGenX: AI-Enabled Cyber Incident Web Portal for Defence
💡 Problem Statement
Defence cyber complaints in India often suffer from delayed response times because they are often "buried in NCRP's civilian load". These delays significantly increase operational risks and leave defence personnel, their families, and veterans vulnerable to cyber threats.

The Critical Need: A dedicated, secure, and swift AI-driven portal is needed for the exclusive and immediate handling of defence-specific cyber incidents.

✨ Solution: NetGenX Defence Cyber Shield
NetGenX is a dedicated Cyber Safety Portal built for the Indian defence ecosystem—personnel, families, and veterans. It aims to provide instant threat analysis using AI/ML and ensure immutable, tamper-proof evidence storage using a combination of Blockchain and IPFS.

Innovation Highlights
Tamper-Proof, Auditable Evidence: Leverages Blockchain + IPFS for decentralized storage and immutable proof of existence, ownership, and timestamp.

Rapid Threat Analysis: AI-powered analysis classifies threats in under <2 seconds.

Real-time Escalation: Instant integration and escalation to CERT-Army for immediate response.

Multi-Format Forensics: Capable of analyzing evidence in various formats, including Text, Audio, Video, and Files.

💻 Technical Approach
Architecture Flow
The system follows a three-group methodology: IPFS Storage, AI/ML Analysis, and Reporting/Blockchain.

Decentralized Upload (IPFS Storage Group):

Users securely upload files via a React UI.

Files are stored on IPFS (InterPlanetary File System) to generate a Unique, Immutable Content ID (CID).

AI-Powered Scanning (AI/ML Analysis Group):

The file is retrieved, and Threat Analysis is performed.

A Python & TensorFlow model analyzes file content using TF-IDF (Term Frequency-Inverse Document Frequency) to generate a Threat Report and assign a Severity/Risk Score.

Immutable Ledger & Response (Reporting & Blockchain Group):

The CID and the AI Report are logged onto the Ethereum Blockchain via a Solidity Smart Contract, creating a permanent audit trail (e.g., using a hashmap: CID -> (time, Record)).

Automated Response: If the Risk Score Exceeds a Threshold, an automatic Alert is Sent to CERT-Army, and the user is provided with actionable Mitigation Steps. Otherwise, the alert is skipped.

All entries get permanent access for Audit and Verification.

Tech Stack
The project leverages a robust and proven technology stack:

Category	Technology	Purpose
Frontend	HTML5, JavaScript (JS), React, Zustand	User Interface, state management, and interaction.
Backend/API	Node.js (JS), Express.js (ex)	Server-side logic and REST APIs.
Blockchain	Ethereum, Solidity	Immutable ledger for CID/Report logging, Smart Contracts.
AI/ML	Python, TensorFlow, TF-IDF	Threat analysis, risk scoring, pattern detection.
Decentralized Storage	IPFS	Tamper-proof, decentralized storage of uploaded files.
Cloud	AWS	Deployment and infrastructure hosting.

Export to Sheets
🚀 Future Plans
The team is committed to continuous enhancement for future-proof security:

Preventive Detention: Use Cyber Threat Intelligence (CTI) and predictive AI to preemptively block threats.

Autonomous Operations: Enable AI-driven threat hunting and automated deception techniques.

Future-Proof Security: Upgrade to quantum-resistant cryptography.

🎯 Target Audience
The portal's primary users include:

Defence Personnel

Defence Personnel Families

Defence Veterans

CERT-Army (for incident response)

📹 Demo Video
Watch the complete demonstration of the NetGenX portal's features and workflow:
https://www.youtube.com/watch?v=Q9UzPYigs1U
Future of Cyber Defense: Leveraging AI for Enhanced Security

This video discusses how AI is transforming cybersecurity, which is the core concept of the NetGenX portal.

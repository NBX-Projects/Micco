# Privacy Policy — Micco (NBX Projects)

**Last updated:** October 2026  
**Organization:** NBX Projects  
**Project:** Micco (https://github.com/NBX-Projects/Micco)

---

## 1. Overview
Micco is an open-source real-time communication platform developed by NBX Projects, built with privacy, data sovereignty, and security in mind. This Privacy Policy explains how information is handled when using official instances or self-hosted servers of Micco.

---

## 2. Information We Collect
- **Account Information:** When you register on an instance, we collect an email address and a hashed password (salted via bcrypt) for authentication purposes.
- **Real-Time Voice and Video:** Voice chat (via LiveKit SFU) and P2P screen sharing (WebRTC) are transmitted in real time. **We do not record, store, or monitor audio or video streams.**
- **Messages & Content:** Chat messages sent in channels are stored in the instance's database (PostgreSQL) strictly for chat history display to channel members.
- **Audit & Connection Logs:** Basic operational logs (such as IP addresses and connection timestamps) may be recorded for audit and security monitoring against unauthorized access.

---

## 3. Data Storage & Sovereignty
- **Self-Hosting:** Users and organizations have full sovereignty to host their own Micco backend and database using our provided Docker configurations. In self-hosted setups, no data is sent to NBX Projects.
- **Data Sharing:** We do not sell, rent, or monetize personal user data. Data is never shared with third parties for marketing purposes.

---

## 4. Open Source and Code Integrity
Micco binaries and releases are open-source. Automated build pipelines are executed publicly via GitHub Actions, and releases are digitally signed to ensure software integrity and protect users against tampering.

---

## 5. Contact & Questions
For privacy questions, feature requests, or data deletion requests, please open an issue or discussion on our official repository:  
https://github.com/NBX-Projects/Micco

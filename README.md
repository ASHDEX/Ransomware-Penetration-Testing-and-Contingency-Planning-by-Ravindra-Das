# Ransomware Penetration Testing and Contingency Planning

Study notes for *Ransomware Penetration Testing and Contingency Planning* by Ravindra Das. Covers adversarial simulation of ransomware attack chains, defensive architecture design, and contingency planning for ransomware incidents.

## Contents

Notes are maintained in the accompanying HTML file — converted from original study materials.

## Key Topics

### Ransomware Attack Chain Simulation

- Initial access techniques: phishing, RDP exploitation, VPN appliance CVEs
- Privilege escalation and lateral movement for pre-ransomware staging
- Data exfiltration prior to encryption (double extortion model)
- Encryption logic: symmetric key generation, RSA wrapping, and C2 key escrow
- Shadow copy deletion and backup disruption techniques

### Penetration Testing Methodology for Ransomware Scenarios

| Phase | Techniques |
|---|---|
| Reconnaissance | OSINT, exposed service enumeration, AD mapping |
| Initial Access | Phishing simulation, credential stuffing, exploiting internet-facing apps |
| Persistence | Registry keys, scheduled tasks, WMI subscriptions |
| Lateral Movement | PsExec, WMI, SMB, RDP pivoting |
| Impact Simulation | Encryption simulation, backup deletion, ransom note drop |

### Defensive Architecture

- Network segmentation to contain ransomware spread
- Immutable backup strategies: 3-2-1 rule, air-gapped backups, backup integrity verification
- Endpoint Detection & Response (EDR) tuning for ransomware behavioral indicators
- Email security: attachment sandboxing, DMARC/DKIM enforcement
- Privileged Access Management (PAM) to limit blast radius

### Contingency Planning

- Business continuity and disaster recovery (BC/DR) plan components
- Recovery Time Objective (RTO) and Recovery Point Objective (RPO) definition
- Ransomware-specific IR playbook structure
- Tabletop exercise design for ransomware scenarios
- Cyber insurance considerations and notification obligations

### Post-Incident Activities

- Forensic evidence preservation for law enforcement
- Root cause analysis and attacker attribution indicators
- Negotiation considerations (pay vs. recover decision framework)
- Post-incident hardening and lessons-learned documentation

## Author

ASHDEX — Security Researcher & Architect | DFIR · Ransomware Response
[ashdex.com](https://ashdex.com)

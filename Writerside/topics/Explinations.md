# Explanations

## Difference Between Investigation Types

### Criminal Investigation
- **Focus:** Investigating activities that violate criminal laws (e.g., hacking, fraud).
- **Goal:** Collect evidence admissible in court to prosecute offenders.
- **Example:** Prosecution of a cybercriminal for unauthorized access.

### Civil Investigation
- **Focus:** Resolving disputes between private parties (e.g., contract breaches, IP theft).
- **Goal:** Provide evidence for lawsuits or settlements.
- **Example:** Evidence collection for a lawsuit over software piracy.

### Administrative Investigation
- **Focus:** Internal organizational compliance (e.g., policy violations).
- **Goal:** Address internal issues and enforce policies.
- **Example:** Reviewing employee actions for policy breaches.

---

## Role of Computer Forensics in Investigations

### Administrative Investigations
- Identifies policy violations or insider threats.
- Analyzes logs, emails, and access history for internal disciplinary actions.

### Criminal Investigations
- Recovers deleted files and digital footprints.
- Collects admissible evidence while maintaining the chain of custody.

---

## Difference Between IDS and IPS

### IDS (Intrusion Detection System)
- Monitors network traffic and generates alerts for suspicious activity.
- **Passive:** Detects but does not block threats.

### IPS (Intrusion Prevention System)
- Monitors traffic and actively blocks malicious actions in real-time.
- **Proactive:** Prevents threats before they affect the system.

---

## Role of SIEM (Security Information and Event Management)
- Aggregates and correlates logs from various systems.
- Provides real-time alerts for security incidents.
- Assists with compliance reporting (e.g., PCI-DSS, HIPAA).

---

## Reasons Behind Continuous Monitoring and Importance of Logs

### Reasons for Continuous Monitoring
- Detect unauthorized access and suspicious activities in real time.
- Ensure regulatory compliance and system integrity.

### Importance of Logs
- Provide forensic evidence for investigations.
- Help identify patterns of malicious activity for prevention.

---

## Importance of Backups and Offsite Storage
- **Backups:** Protect against data loss from hardware failures, cyberattacks, or disasters.
- **Offsite Storage:** Ensures data remains safe during physical disasters like fires or floods, reducing single points of failure.

---

## Difference Between Full, Differential, and Incremental Backups

### Full Backup
- **Definition:** A complete copy of all data.
- **When to Use:** As a periodic baseline for restoration.

### Differential Backup
- **Definition:** Backs up changes since the last **full backup**.
- **When to Use:** When faster recovery is needed with moderate storage use.

### Incremental Backup
- **Definition:** Backs up changes since the **last backup (full or incremental)**.
- **When to Use:** For efficient storage and faster backup processes.

---

## Recovery Site Strategies

### Hot Site
- Fully operational and pre-configured for immediate failover.
- **Use Case:** Critical operations requiring zero downtime.

### Warm Site
- Pre-configured but requires some setup before use.
- **Use Case:** Semi-critical systems with moderate downtime tolerance.

### Cold Site
- An empty facility with no pre-installed hardware.
- **Use Case:** Cost-effective option for non-critical operations.

### Mobile Site
- Portable facility equipped for temporary operations.
- **Use Case:** Disaster recovery in remote or inaccessible areas.

### Cloud Backup
- Stores data in remote cloud environments.
- **Use Case:** Highly scalable and cost-effective for disaster recovery.

---

## RAID (Redundant Array of Independent Disks)

### Why RAID 0 Is Not Real RAID
- **RAID 0:** Offers striping without redundancy, improving performance but providing no fault tolerance.
- **True RAID:** Requires redundancy to protect against data loss.

---

## Difference Between NAS and SAN

### NAS (Network Attached Storage)
- Storage shared over a network via standard file systems (e.g., NFS, SMB).
- **Use Case:** Suitable for small to medium-scale file storage.

### SAN (Storage Area Network)
- High-speed network providing block-level storage.
- **Use Case:** Ideal for enterprise-level applications requiring high performance.

---

## Disaster Recovery Testing Plans

### Read-Through/Tabletop
- **Definition:** Discuss recovery steps without executing them.
- **Use Case:** Low-cost review of procedures.

### Walk-Through
- **Definition:** Physically review recovery plans and processes.
- **Use Case:** Ensure all steps are understood.

### Simulation
- **Definition:** Simulate a disaster without affecting operations.
- **Use Case:** Test readiness for specific scenarios.

### Parallel
- **Definition:** Operate recovery systems alongside production systems without disrupting them.
- **Use Case:** Validate recovery processes while maintaining operations.

### Full Interruption
- **Definition:** Fully halt operations to test recovery systems.
- **Use Case:** Comprehensive validation of disaster recovery capabilities.

---

## Reason for Using Different Devices When Traveling Abroad
- Devices may be vulnerable to surveillance or tampering in certain countries (e.g., China, USA, Australia).
- Using separate devices reduces risks to sensitive data and organizational systems.

---

## Role of Training and Education in Operations Security
- Builds awareness of security policies and best practices.
- Helps employees recognize and respond to threats effectively.
- Ensures proper handling of tools, systems, and incidents.
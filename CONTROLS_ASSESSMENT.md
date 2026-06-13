# Botium Toys: Cybersecurity Controls Assessment

This internal audit evaluates the current IT asset environment of Botium Toys, identifies security gaps, and classifies mitigation priorities to reduce the organization's overall risk score from 8/10.

## 1. Administrative Controls
| Control Name | Control Type & Explanation | Needs Implementation (X) | Priority Level |
| :--- | :--- | :---: | :---: |
| **Least Privilege** | Preventative; ensures staff and vendors only access assets/data required for their direct jobs. | **X** | **High** |
| **Disaster Recovery Plans** | Corrective; ensures business continuity and limits downtime during a security incident. | **X** | **High** |
| **Password Policies** | Preventative; establishes complexity rules to mitigate brute-force and dictionary attacks. | **X** | **High** |
| **Access Control Policies** | Preventative; safeguards data confidentiality and asset integrity. | **X** | **High** |
| **Account Management** | Preventative; limits attack surface from disgruntled or former employees. | **X** | **High** |
| **Separation of Duties** | Preventative; prevents privilege abuse by ensuring no single user holds excessive access. | **X** | **Medium** |

## 2. Technical Controls
| Control Name | Control Type & Explanation | Needs Implementation (X) | Priority Level |
| :--- | :--- | :---: | :---: |
| **Firewall** | Preventative; filters malicious perimeter traffic from entering the internal corporate network. | | **N/A** (In Place) |
| **Intrusion Detection System (IDS)** | Detective; alerts the IT team to anomalous traffic patterns and potential breaches. | **X** | **High** |
| **Encryption** | Deterrent; protects sensitive transactional data and online e-commerce card payments. | **X** | **High** |
| **Backups** | Corrective; secures historical business data restoration to support disaster recovery execution. | **X** | **High** |
| **Password Management System** | Corrective; automates enforcement of credential cycling, complexity, and lockouts. | **X** | **High** |
| **Antivirus (AV) Software** | Corrective; scans, detects, and quarantines malicious code payloads on end-user endpoints. | **X** | **High** |
| **Manual Monitoring & Maintenance** | Preventative/Corrective; human-led monitoring required specifically to sustain legacy systems. | **X** | **Medium** |

## 3. Physical Controls
| Control Name | Control Type & Explanation | Needs Implementation (X) | Priority Level |
| :--- | :--- | :---: | :---: |
| **Locks** | Preventative; enforces physical boundaries to protect critical hardware, servers, and inventory. | **X** | **High** |
| **Locking Cabinets** | Preventative; safeguards physical network infrastructure gear from tampering. | **X** | **High** |
| **Fire Detection & Prevention** | Detective/Preventative; environmental sensors to guard assets against catastrophic fire damage. | **X** | **High** |
| **CCTV Surveillance** | Preventative/Detective; provides detective audit trails for physical incident investigations. | **X** | **Medium** |
| **Adequate Lighting** | Deterrent; visibility enhancement around physical perimeters to discourage intrusion. | **X** | **Medium** |
| **Time-Controlled Safe** | Deterrent; minimizes the physical exposure and operational footprint of financial assets. | **X** | **Medium** |
| **Alarm Service Signage** | Deterrent; psychological barrier lowering the perceived success rate of physical asset theft. | **X** | **Low** |

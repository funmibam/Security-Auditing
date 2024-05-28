# Security-Auditing
# Security Audit for Botium Toys

## Scope and Goals of the Audit

### Scope
The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

### Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.

## Current Assets
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

## Risk Assessment

### Risk Description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### Control Best Practice
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk Score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

# Controls and Compliance checklist

| Control                             | Explanation                                                                                                                                                    | Yes        | No        |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|-----------|
| Least Privilege                     | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach.                                            |            | ❌        |
| Disaster Recovery Plans             | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity.                                                      |            | ❌        |
| Password Policies                   | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |            | ❌        |
| Separation of Duties                | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll. |            | ❌        |
| Firewall                            | The existing firewall blocks traffic based on an appropriately defined set of security rules.                                                                  | ✅         |           |
| Intrusion Detection System (IDS)    | The IT department needs an IDS in place to help identify possible intrusions by threat actors.                                                                  |            | ❌        |
| Backups                             | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.                                               |            | ❌        |
| Antivirus Software                  | Antivirus software is installed and monitored regularly by the IT department.                                                                                   | ✅         |           |
| Manual Monitoring for Legacy Systems| The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule for this task and procedures/policies related to intervention are unclear, which could place these systems at risk of a breach. |            | ❌        |
| Encryption                          | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information.                                               |            | ❌        |
| Password Management System          | There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues. |            | ❌        |
| Locks (Offices, Storefront, Warehouse) | The store’s physical location, which includes the company’s main offices, store front, and warehouse of products, has sufficient locks.                         | ✅         |           |
| Closed-circuit Television (CCTV) Surveillance | CCTV is installed/functioning at the store’s physical location.                                                                                               | ✅         |           |
| Fire Detection/Prevention (Fire Alarm, Sprinkler System, etc.) | Botium Toys’ physical location has a functioning fire detection and prevention system.                                                                       | ✅         |           |

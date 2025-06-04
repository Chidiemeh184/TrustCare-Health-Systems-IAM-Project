# TrustCare Health Systems - IAM & Active Directory Implementation Project

[![GitHub](https://img.shields.io/badge/GitHub-Project%20Repository-blue?style=flat&logo=github)](https://github.com/Chidiemeh184/TrustCare-Health-Systems-IAM-Project)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow.svg)]()

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Company Background](#company-background)
- [Project Structure](#project-structure)
- [Implementation Phases](#implementation-phases)
- [Skills Demonstrated](#skills-demonstrated)
- [Documentation](#documentation)
- [Contact Information](#contact-information)

---

## 🏥 Project Overview

This repository documents my comprehensive IAM & Active Directory implementation project for **TrustCare Health Systems**, a fictional healthcare organization used to demonstrate real-world IAM engineering capabilities. The project encompasses domain structure design, physical infrastructure planning, organizational unit architecture, security implementation, and advanced IAM platform integration.

[![View Company Slides](https://img.shields.io/badge/📊_View_Company_Slides-Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/S2MGklpLjUfkLbXQ4UtUwJ/TrustCare-Health-Systems-Slides?node-id=1103-1218&t=2Tsikco2pbxR6ma3-1)


**Project Duration:** [05/27/2025] - [08/27/2025]  
**Environment:** HomeLab - VirtualBox 7.0.17 (Apple Intel) Lab Environment  
**Domain:** trustcare.corp  
**Scope:** Enterprise-level AD implementation with healthcare compliance requirements

---

## 🏢 Company Background

### TrustCare Health Systems, Inc.

**Company Profile:**
- **Founded:** 2005
- **Headquarters:** Atlanta, GA
- **Type:** Healthcare services and pharmacy operations
- **Annual Revenue:** $820 million (2024)
- **Employees:** 3,200 nationwide
- **Stock Symbol:** TCHS (NASDAQ)

**Mission Statement:**  
*"To deliver accessible, affordable healthcare solutions that improve patient outcomes through innovative pharmacy services and integrated health management."*

### Business Operations

**Core Business Units:**
- **Retail Pharmacy Division** (60% of revenue) - 175 physical locations across 15 states
- **Digital Health Services** (15% of revenue) - Online prescription management and telehealth
- **Specialty Pharmacy** (20% of revenue) - Complex medication management and rare disease treatments
- **Clinical Services** (5% of revenue) - Medication therapy management and vaccination programs

### Geographic Distribution
- **Headquarters:** Atlanta, GA
- **Regional Offices:** Boston, Chicago, Los Angeles, Dallas
- **Distribution Centers:** Atlanta (Primary), Phoenix (Secondary), Nashville (Backup)
- **Major Offices:** New York, San Francisco, Denver, Miami, Seattle

### IT Infrastructure Requirements
- **Users:** ~3,500 total accounts
- **Workstations:** 3,500 (mixture of desktops and laptops)
- **Servers:** 250 (physical and virtual)
- **Compliance:** HIPAA, HITECH, PCI-DSS, SOX
- **Security:** Multi-factor authentication, privileged access management

---

## 📁 Project Structure

```
TrustCare-Health-Systems-IAM-Project/
├── README.md (this file)
├── docs/
│   ├── company-background/
│   └── project-overview/
├── step-a-domain-structure/
│   ├── README.md
│   ├── screenshots/
├── step-b-physical-infrastructure/
│   ├── README.md
│   ├── screenshots/
│   ├── site-topology/
│   └── documentation/
├── step-c-ou-structure/
│   ├── README.md
│   ├── screenshots/
│   ├── ou-designs/
│   └── documentation/
├── step-d-security-implementation/
│   ├── README.md
│   ├── screenshots/
│   ├── security-configs/
│   └── documentation/
├── xtensys-job-requirements/
│   ├── README.md
│   ├── junior-level-tasks/
│   ├── mid-level-tasks/
│   ├── senior-level-tasks/
│   └── documentation/
└── resources/
    ├── scripts/
    ├── templates/
    └── references/
```

---

## 🚀 Implementation Phases

### [Step A: Domain Structure Design](./step-a-domain-structure/)
**Status:** 🟢 Completed

Design and implementation of the Active Directory domain structure for TrustCare Health Systems, including forest consolidation strategy for acquired companies.

**Key Deliverables:**
- [x] Domain architecture diagrams
- [x] Forest trust configuration
- [x] DNS structure implementation
- [x] Migration planning documentation
 
**Documentation:** [Link to detailed documentation](./step-a-domain-structure/README.md)

---

### [Step B: Physical Infrastructure](./step-b-physical-infrastructure/)
**Status:** 🟢 Completed 

Design and deployment of domain controllers across TrustCare's geographic locations with proper site topology and replication strategies.

**Key Deliverables:**
- [x] 14 domain controllers across 12 locations
- [x] Site and services configuration
- [x] Replication topology optimization
- [x] High availability implementation

**Documentation:** [Link to detailed documentation](./step-b-physical-infrastructure/README.md)

---

### [Step C: Organizational Unit Structure](./step-c-ou-structure/)
**Status:** ⏳ In Progress 

Implementation of hierarchical OU structure supporting location-based, department-based, and resource-based organization with proper delegation of control.

**Key Deliverables:**
- [ ] Multi-tiered OU hierarchy
- [ ] Delegation of control implementation
- [ ] Group Policy inheritance planning
- [ ] Security boundary establishment

**Screenshots:** [X] screenshots attached  
**Documentation:** [Link to detailed documentation](./step-c-ou-structure/README.md)

---

### [Step D: Security Implementation](./step-d-security-implementation/)
**Status:** ❌ Not Started

Comprehensive security hardening including attack simulation, defense implementation, and healthcare-specific compliance controls.

**Key Deliverables:**
- [ ] Advanced threat protection
- [ ] Privileged access management
- [ ] HIPAA compliance controls
- [ ] Security monitoring and auditing

**Screenshots:** [X] screenshots attached  
**Documentation:** [Link to detailed documentation](./step-d-security-implementation/README.md)

---

### [Xtensys Job Requirements Implementation](./xtensys-job-requirements/)
**Status:** ❌ Not Started

Real-world task implementation covering Junior to Senior level IAM responsibilities based on actual job requirements from Xtensys.

#### [Junior Level Tasks](./xtensys-job-requirements/junior-level-tasks/)
**Focus Areas:**
- [ ] Directory Services management (Active Directory/Azure AD)
- [ ] Basic IAM platform administration (Duo, Beyond Trust)
- [ ] User lifecycle management and troubleshooting
- [ ] Security policy enforcement and monitoring

#### [Mid Level Tasks](./xtensys-job-requirements/mid-level-tasks/)
**Focus Areas:**
- [ ] Advanced PowerShell scripting and automation
- [ ] Complex IAM integrations and workflows
- [ ] Security framework implementation
- [ ] Compliance auditing and reporting

#### [Senior Level Tasks](./xtensys-job-requirements/senior-level-tasks/)
**Focus Areas:**
- [ ] Enterprise architecture design
- [ ] Zero-trust implementation
- [ ] Advanced threat detection and response
- [ ] Strategic IAM roadmap development

**Screenshots:** [X] screenshots attached  
**Documentation:** [Link to detailed documentation](./xtensys-job-requirements/README.md)

---

## 🎯 Skills Demonstrated

### Technical Skills
- **Active Directory:** Domain design, forest management, site topology, replication
- **IAM Platforms:** Azure AD, Okta, SailPoint, CyberArk, Ping Identity, ForgeRock
- **Security:** Privileged access management, MFA implementation, threat detection
- **Scripting:** PowerShell, Python automation for IAM tasks
- **Compliance:** HIPAA, HITECH, healthcare data protection

### Professional Skills
- **Documentation:** Comprehensive technical documentation and procedures
- **Project Management:** Phased implementation with clear deliverables
- **Problem Solving:** Real-world scenario troubleshooting and resolution
- **Communication:** Clear presentation of technical concepts and solutions

---

## 📚 Documentation

### Quick Access Links
- [📊 Project Dashboard](./docs/project-dashboard.md)
- [🏗️ Architecture Overview](./docs/architecture-overview.md)
- [📋 Task Completion Status](./docs/task-status.md)
- [📸 Screenshot Gallery](./docs/screenshot-gallery.md)
- [📝 Lessons Learned](./docs/lessons-learned.md)

### Implementation Guides
- [🔧 Lab Setup Instructions](./docs/lab-setup.md)
- [⚙️ Configuration Templates](./resources/templates/)
- [🔨 PowerShell Scripts](./resources/scripts/)
- [📖 Reference Materials](./resources/references/)

---

## 📈 Project Metrics

| Metric | Target | Current Status |
|--------|--------|----------------|
| Domain Controllers Deployed | 14 | ⏳ [X]/14 |
| Users Migrated | 3,500 | ⏳ [X]/3,500 |
| Applications Integrated | 12 | ⏳ [X]/12 |
| Security Policies Implemented | 25 | ⏳ [X]/25 |
| Documentation Pages | 50+ | ⏳ [X]/50+ |

---

## 🔗 Related Projects

- [Healthcare IAM Compliance Framework](link-to-related-project)
- [Multi-Platform IAM Integration Lab](link-to-related-project)
- [Active Directory Security Assessment Tools](link-to-related-project)

---

## 📞 Contact Information

**Project Author:** [Chidi Emeh]  
**Email:** [chidiemeh184@gmail.com]  
**LinkedIn:** [linkedin.com/in/chidiemeh](https://www.linkedin.com/in/chidi-e-2307359a/)  
**Portfolio(Coming soon):** [rdmp.com](https://rdmp.com)

---

## 📄 License

This project is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

### Summary:
- ✅ **Clone and modify** for personal learning
- ✅ **Use in portfolios** and job applications  
- ✅ **Share with attribution** for educational purposes
- ❌ **Create paid courses** without permission
- ❌ **Monetize on YouTube** without permission
- ❌ **Commercial training use** without permission

**Need commercial permissions?** Contact: [chidiemeh184@gmail.com]

---

## 🙏 Acknowledgments

- **TrustCare Health Systems** - Fictional company scenario for realistic implementation experience
- **Microsoft Documentation** - Active Directory implementation best practices
- **Healthcare IT Community** - HIPAA compliance guidance and security frameworks
- **IAM Vendor Documentation** - Platform-specific implementation guides

---

**Last Updated:** [05/27/2025]  
**Version:** 1.0.0

---

*This project demonstrates practical, hands-on experience with enterprise Active Directory implementation and IAM platform integration in a healthcare environment. All configurations and scenarios are designed to reflect real-world requirements and industry best practices.*

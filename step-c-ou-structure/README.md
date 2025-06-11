# Organizational Unit Structure

---
### ⭐️ Objectives
OU Structure  
Design the OU structure of the organization while considering scalability for the following areas: 
1. Location-based
2. Department-based
3. Resource type-based (servers, workstattion and users)

Group Policy Requirements 
1. Role-based access controls
2. Enhanced security for PHI/PII handling workstations
3. Strict password and account lockout policies

---
### ✅ Key Deliverables:
Implementation of hierarchical OU structure supporting location-based, department-based, and resource-based organization with proper delegation of control.
- [x] Multi-tiered OU hierarchy
- [ ] Delegation of control implementation
- [ ] Group Policy inheritance planning
- [ ] Security boundary establishment

---
### 🧠 Key Takeaways 
1. OU is used for organization and setting security policies
2. OUs are different from containers 
3. In progress ...

---
### 📁 OU Structure
Below is the architectural design of OU structure based on the above requirements  
```
# Active Directory OU Structure Design

# Colors:
#   - BLUE:   Top-Level OUs
#   - GREEN:  Location-Based
#   - ORANGE: Department-Based
#   - YELLOW: Resource Type-Based
#   - GRAY:   General Notes/Connectors

#---------------------------------------------------------------------------------------
# Top-Level OU Structure
# - Establishes the main organizational divisions
#---------------------------------------------------------------------------------------

BLUE TrustCare Health Systems
#   |---BLUE Locations     # For location-specific organization
#   |---BLUE Departments   # For department-specific organization
#   |---BLUE Resources     # For managing resources (servers, workstations)
#   |---BLUE ServiceAccounts # For service accounts

#---------------------------------------------------------------------------------------
# 1. Location-Based OU Structure
# - Organizes objects by physical location
#---------------------------------------------------------------------------------------

BLUE Locations
#   |---GREEN Atlanta
#   |   |---GREEN Atlanta-HQ   # Headquarters
#   |   |---GREEN Atlanta-DC1  # Primary DC
#   |---GREEN Boston
#   |---GREEN Chicago
#   |---GREEN Los Angeles
#   |---GREEN Dallas
#   |---GREEN Phoenix
#   |---GREEN Nashville
#   |---GREEN New York
#   |---GREEN San Francisco
#   |---GREEN Denver
#   |---GREEN Miami
#   |---GREEN Seattle

#---------------------------------------------------------------------------------------
# 2. Department-Based OU Structure
# - Organizes user accounts by department
#---------------------------------------------------------------------------------------

BLUE Departments
#   |---ORANGE Executive
#   |---ORANGE Finance
#   |---ORANGE HumanResources
#   |---ORANGE InformationTechnology
#   |---ORANGE Operations
#   |---ORANGE SalesMarketing
#   |---ORANGE PharmacyServices
#   |---ORANGE ResearchDevelopment
#   |---ORANGE LegalCompliance
#   |---ORANGE CustomerSupport

#---------------------------------------------------------------------------------------
# 3. Resource Type-Based OU Structure
# - Organizes computer and server objects
#---------------------------------------------------------------------------------------

BLUE Resources
#   |---YELLOW Workstations
#   |   |---YELLOW Desktops
#   |   |---YELLOW Laptops
#   |   |---YELLOW PharmacyTerminals # Special workstations
#   |---YELLOW Servers
#   |   |---YELLOW DomainControllers
#   |   |---YELLOW FileServers
#   |   |---YELLOW ApplicationServers
#   |   |---YELLOW DatabaseServers
#   |   |---YELLOW WebServers
#   |   |---YELLOW SpecialtyHealthServers

#---------------------------------------------------------------------------------------
# Additional Notes:
# - This is a hierarchical structure, OUs can be nested further as needed.
# - Group Policy Objects (GPOs) will be linked at appropriate OU levels to enforce settings.
# - Delegation of control will be used to grant specific administrative permissions at the OU level.
# - Consider creating sub-OUs within Departments for more granular management (e.g., Finance -> Accounting, Payroll).
# - The "ServiceAccounts" OU is for managing service accounts used by applications/services.
#---------------------------------------------------------------------------------------
```

---
### 📂 Top Level OUs 
![Image](screenshots/1-Top-Level-OUs.png)

---
### 📂 Location Based OUs 
![Image](screenshots/2-Location-Based-OUs.png)

---
### 📂 Department Based OUs 
![Image](screenshots/3-Department-Based-OUs.png)

---
### 📂 Resource Based OUs 
![Image](screenshots/4-Resource-Based-OUs.png)
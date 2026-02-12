# Entra ID Integration & Identity Management (AZ-104)

## 📌 Overview
This project demonstrates how to integrate applications with Microsoft Entra ID, manage users and groups, configure Conditional Access policies, enforce Multi-Factor Authentication (MFA), and monitor authentication activity. It reflects real-world identity and access management (IAM) practices used in production Azure environments.

## 🎯 Objectives
- Create users and groups in Entra ID  
- Register and configure an application  
- Assign users and groups to enterprise applications  
- Enforce Conditional Access and MFA  
- Monitor sign-in activity and security events  

## 🧰 Azure Services Used
- Microsoft Entra ID  
- App Registrations  
- Enterprise Applications  
- Conditional Access  
- Microsoft Authenticator / MFA  
- Sign-in Logs  


## 🏗 Architecture Overview

- End Users authenticate to the application via Microsoft Entra ID
- Entra ID manages users, groups, and application authentication
- Application Registration enables OAuth/OpenID Connect sign-in
- Enterprise Application controls access using assigned groups
- Conditional Access enforces security policies
- Multi-Factor Authentication (MFA) protects sign-ins
- Sign-in Logs provide monitoring and auditing of authentication activity


## 🛠 Implementation Steps

### 1️⃣ Create Users & Groups in Entra ID
Created multiple users and assigned them to role-based groups.




### 2️⃣ Register an Application in Entra ID
Registered a web application and configured redirect URIs, API permissions, and client secrets.




### 3️⃣ Assign Users & Groups to the Application
Assigned Entra groups to the Enterprise Application for access control.




### 4️⃣ Configure Conditional Access
Created Conditional Access policy enforcing MFA and access conditions.




### 5️⃣ Enable MFA
Enabled MFA for users and verified sign-in prompts.




### 6️⃣ Monitor Sign-in Activity
Reviewed sign-in logs to track authentication success and failures.




## ✅ Outcomes
- Centralised identity management using Entra ID  
- Secure authentication enforced with Conditional Access and MFA  
- Role-based access using groups  
- Auditable sign-in activity for security monitoring  



## 📚 AZ-104 Skills Demonstrated
- Identity and Access Management (IAM)  
- Microsoft Entra ID administration  
- Application registration and authentication  
- Conditional Access policy design  
- MFA enforcement  
- Security monitoring  



## 🧹 Cleanup (Important to Avoid Charges)
Delete test users, application registration, and Conditional Access policies when finished:

- Entra ID → Users → Delete test users  
- Entra ID → App registrations → Delete test app  
- Entra ID → Conditional Access → Disable/Delete policy  



## 🔗 References
- https://learn.microsoft.com/entra  
- https://learn.microsoft.com/azure/active-directory  

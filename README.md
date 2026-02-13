# 🔐 Project 4: Entra ID Integration & Identity Management (AZ-104 Demo)

## 📌 Overview
This project demonstrates how to integrate an application with Microsoft Entra ID for authentication and access control. It covers user and group management, app registration, API permissions, Conditional Access (MFA), and sign-in monitoring.


## 🏗 Architecture Overview
- Users authenticate with Microsoft Entra ID  
- Application registered in App Registrations  
- Permissions granted via Microsoft Graph  
- Access controlled using Conditional Access (MFA)  
- Users assigned through Enterprise Applications  
- Authentication activity monitored via Sign-in Logs  


## 🛠 Technologies Used
- Microsoft Entra ID (Azure AD)  
- App Registrations  
- Enterprise Applications  
- Conditional Access (MFA)  
- Microsoft Graph API  
- Azure Portal  


## ✅ Implementation Steps

### 1️⃣ Create Users & Groups
Created test users and security groups:
- admin-104  
- dev-104  
- reader-104  

**Screenshots:**
- `/screenshots/entraid-users.png`  
- `/screenshots/entraid-groups.png`  


### 2️⃣ Register Application in Entra ID
Registered application:  
**az104-demo-app**

**Screenshot:**  
- `/screenshots/app-registration.png`


### 3️⃣ Configure API Permissions
Configured Microsoft Graph permissions:
- User.Read  
- User.Read.All  
Admin consent granted.

**Screenshot:**  
- `/screenshots/api-permissions.png`


### 4️⃣ Create Client Secret
Generated client secret for application authentication.

**Screenshot:**  
- `/screenshots/client-secret.png`


### 5️⃣ Assign Users to Application
Assigned users to Enterprise Application.

**Screenshot:**  
- `/screenshots/users-assigned-enterprise-application.png`


### 6️⃣ Configure Conditional Access (Require MFA)
Created Conditional Access policy:
- Applied to specific users  
- Targeted az104-demo-app  
- Required Multi-Factor Authentication (MFA)

**Screenshots:**  
- `/screenshots/conditional-access-policy.png`  
- `/screenshots/conditional-access-mfa.png`


### 7️⃣ Verify Sign-In Logs
Validated authentication and Conditional Access enforcement.

**Screenshot:**  
- `/screenshots/sign-in-logs.png`


## 🔐 Security Features Demonstrated
- Role-based access control  
- Application authentication  
- Conditional Access policy  
- MFA enforcement  
- Sign-in monitoring  


## 🧠 What This Project Demonstrates
- Real-world Entra ID configuration  
- Identity & Access Management skills  
- Azure security fundamentals  
- Conditional Access & MFA setup  
- Enterprise-ready identity design  

- https://learn.microsoft.com/entra  
- https://learn.microsoft.com/azure/active-directory  

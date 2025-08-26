# Automate Process for AAD User Creation and Group Assignment

This repository contains documentation (`.docx` file) that explains how to **automate the process of creating Azure Active Directory (AAD) users and assigning them to groups with licenses** using **Power Automate**.

## 📄 Document Overview
The provided Word document includes:
- **Purpose**: Automating AAD user creation and license assignment.  
- **Plan**: Using a Power Automate flow triggered by new items in a SharePoint list.  
- **Steps Covered**:
  1. Creating a cloud automated flow triggered by SharePoint.  
  2. Initializing a variable to generate random passwords.  
  3. Using the **Azure AD connector** to create a user with required attributes.  
  4. Setting up a **security group in Azure AD** for license assignment.  
  5. Adding the user to the license group via Power Automate.  
  6. Sending details by email.  

## 🛠️ Requirements
- **Microsoft 365 tenant with Azure Active Directory**  
- **Power Automate** access  
- **SharePoint list** to capture user details  
- **Azure AD Security Group** for license assignment  

## 🚀 Usage
1. Open the `.docx` file in this repository.  
2. Follow the step-by-step guide to set up:  
   - SharePoint list for user details  
   - Power Automate flow for automation  
   - Azure AD group for license assignment  

## 📂 Repository Structure
.
├── Automate_Process_for_AAD_user_creation_and_adding_to_AAD_Group.docx
└── README.md

yaml
Copy
Edit

## 📧 Support
If you encounter issues while setting up, refer to Microsoft Docs:  
- [Azure Active Directory Documentation](https://learn.microsoft.com/azure/active-directory/)  
- [Power Automate Documentation](https://learn.microsoft.com/power-automate/)  

---

✨ This repo is intended as a **reference guide** for IT admins looking to simplify user onboarding in Azure Active Directory.

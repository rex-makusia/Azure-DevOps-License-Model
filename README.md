# Azure-DevOps-License-Model
Notes on Azure DevOps License Model

# Azure DevOps Licensing & User Access Levels

## 🎯 Overview

Azure DevOps uses a licensing model based on **access levels** assigned to users. Each user must have an access level to interact with the platform.

---

## 🔐 Access Levels

| Access Level          | Cost                  | Features                                                                 |
|-----------------------|-----------------------|--------------------------------------------------------------------------|
| **Stakeholder**       | Free                  | - Manage work items<br>- View dashboards<br>- Approve pipelines<br>❌ No code access<br>❌ No advanced features |
| **Basic**             | €5.06 / month         | - Full access to Boards, Repos, Pipelines, Artifacts<br>❌ No Test Plans |
| **Basic + Test Plans**| €43.86 / month        | - All Basic features<br>✅ Test management<br>✅ User acceptance testing<br>✅ Test execution/reporting |

---

## 🧑‍💼 Typical Use Cases

- **Stakeholder**: For project managers, business analysts, or clients who only need to:
  - Create and manage work items
  - View dashboards and approve pipelines

- **Basic**: For developers and DevOps engineers needing full access (except test management).

- **Basic + Test Plans**: For QA engineers/test leads who need structured test management tools.

---

## ❓ Why Are New Users Assigned as Stakeholders?

1. **Free Access**: Stakeholder is free and ideal for light collaboration roles.
2. **Cost Optimization**: Prevents unnecessary license costs.
3. **Controlled Permissions**: Ensures limited access by default for security and governance.

---

## 🔄 How to Upgrade a User from Stakeholder to Basic

### Azure DevOps Services (Cloud):
1. Go to **Organization Settings**.
2. Click **Users**.
3. Find the user in the list.
4. Click the **three dots (•••)** next to the user.
5. Select **Change access level**.
6. Choose **Basic** and save.

### Azure DevOps Server (On-Prem):
1. Open **Admin Console** or navigate to **Collection Settings > Access Levels**.
2. Find the user and change their access level to **Basic**.

> 📝 Note:
> - The **first 5 Basic users** in Azure DevOps Services are **free**.
> - Additional Basic users require a paid license.

---

## 🛠 Optional: Automating Access Level Changes

You can automate user management using:
- **Azure DevOps REST API**
- **Azure CLI**
- **PowerShell scripts**
---

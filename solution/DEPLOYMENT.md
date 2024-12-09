# Proposal Builder – Solution Deployment Guide

**Effective Date: 09/12/2024**

This guide provides detailed steps for deploying the **Proposal Builder App** as a managed solution in your Microsoft Power Platform environment.

---

## Prerequisites

Before deploying the managed solution, ensure the following:

1. **Power Platform Environment**:
   - You must have an active **Power Platform** or **Dynamics 365** environment.
   - Administrator or System Customizer access to the target environment.

2. **Solution File**:
   - Download the latest managed solution `.zip` file from the **GitHub Releases** page.

3. **Licensing and Permissions**:
   - Ensure appropriate licenses are assigned to all users who will access the Proposal Builder App.
   - Ensure permissions for customization in the target environment.

---

## Step-by-Step Installation

### 1. Access Power Platform Admin Center
- Navigate to the [Power Platform Admin Center](https://admin.powerplatform.microsoft.com/).
- Select the environment where you want to deploy the solution.

---

### 2. Import the Managed Solution
1. Open the **Power Apps Maker Portal** ([https://make.powerapps.com/](https://make.powerapps.com/)).
2. In the left-hand menu, click **Solutions**.
3. Select **Import Solution** from the command bar.
4. Click **Browse**, then select the downloaded `.zip` solution file.
5. Click **Next** and follow the on-screen instructions.

---

### 3. Review and Confirm Import
- On the Import Solution page:
  - Verify the solution name: **Proposal Builder**.
  - Confirm that the solution is **managed**.
- Click **Import** to begin the deployment process.

---

### 4. Publish Customizations
Once the solution import is complete:
1. Click **Publish All Customizations** to ensure all changes are applied.
2. Verify that the app and its components (e.g., entities, forms, views, and business rules) are available in your environment.

---

## Post-Installation Configuration

### 1. Assign Security Roles
- Navigate to **Settings** > **Users + Permissions** > **Security Roles**.
- Assign the appropriate security role (e.g., **Proposal Builder User**) to users who need access to the app.

### 2. Enable Solution Features
- Review the settings of the Proposal Builder app to configure any required features or integrations specific to your organization.
- Ensure data connections (if applicable) are functional.

### 3. Configure Permissions
- Ensure proper permissions are assigned to users for relevant entities (e.g., Proposals, Estimations).
- Configure user roles and field-level security as needed.

---

## Testing the Installation

1. Open the **Proposal Builder App** from the Apps menu.
2. Create a test record (e.g., Proposal or Estimation) to verify that the solution is working correctly.
3. Confirm tha

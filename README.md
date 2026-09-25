# Microsoft Entra ID Group Management & License Assignment Lab Walkthrough

This guide provides a step-by-step documentation for creating groups in Microsoft Entra ID and assigning Microsoft 365 licenses through group-based licensing[cite: 2, 5].

---

## 📋 Table of Contents
1. [Group Creation in Microsoft Entra ID](#1-group-creation-in-microsoft-entra-id)
2. [Adding Members to the Group](#2-adding-members-to-the-group)
3. [License Administration & Group Assignment](#3-license-administration--group-assignment)

---

## 1. Group Creation in Microsoft Entra ID
Administrators can create security groups to manage user memberships and streamline service assignments.

* **Navigating to Groups:** From the Microsoft Entra admin center, go to **Entra ID** and select **Groups**, then click **New group**[cite: 2].
  
  ![Groups Overview](2.jpg)

* **Group Configuration Parameters:** Setting up the group details as specified below[cite: 3]:
  * **Group type:** Security[cite: 3]
  * **Group name:** `sg-SC300-O365`[cite: 3]
  * **Membership type:** Assigned[cite: 3]
  * **Owners:** Assign your own administrator account as the group owner[cite: 3].
  
  ![New Group Settings](3.jpg)

* **Group Creation Success:** Verifying that the group `sg-SC300-O365` has been successfully created[cite: 4].
  
  ![Group Created Notification](4.jpg)

---

## 2. Adding Members to the Group
Populating the newly created security group with test user accounts for licensing.

* **Selecting Members:** Under **Members**, selecting the **No members selected** text to open the member selection blade[cite: 3].
* **Adding User:** Selecting **Delia Dennis** from the user list and confirming the selection[cite: 3].

---

## 3. License Administration & Group Assignment
Assigning Microsoft 365 licenses to members via group-based license management.

* **Microsoft 365 Admin Center:** Navigating to the Microsoft 365 admin center via `admin.microsoft.com` and accessing **Billing** > **Licenses**[cite: 5].
  
  ![Billing Licenses Overview](5.jpg)

* **Selecting License Type:** Choosing **Microsoft 365 E5 (no Teams)** from the license list[cite: 6].
  
  ![License Details](6.jpg)

* **Assigning License to Group:** Selecting **Assign licenses**, searching for and selecting the `sg-SC300-O365` security group, and completing the assignment[cite: 7].
  
  ![Assign Licenses Blade](7.jpg)

---

## Repository Structure
```text
├── README.md
└── Screenshots/
    ├── 1.png
    ├── 2.jpg
    ├── 3.png
    ├── 4.png
    ├── 5.jpg
    ├── 6.png
    ├── 7.jpg
    └── 8.jpg

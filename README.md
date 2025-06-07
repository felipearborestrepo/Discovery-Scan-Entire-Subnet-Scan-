# Subnet Discovery Scan Project in Tenable

![OIP (1)](https://github.com/user-attachments/assets/032c847d-b401-4c6c-8da4-bee014c00dde)

In this project, we demonstrate how to create a **Host Discovery Scan** in Tenable Vulnerability Management to identify active hosts within a specific subnet range of a **virtual network in Azure**.

_**Inception State:**_ No scan configured to discover subnets.

_**Completion State:**_ Subnet scan created, targets identified, scan launched, and discovery results obtained.

---

# Technology Utilized
- **Tenable.io** – Cloud-based vulnerability management and scanning platform
- **Azure Virtual Network** – Source of the subnet for scanning
- **Internal Network Scanner** – Configured in Tenable

![Screenshot 2025-06-07 111407](https://github.com/user-attachments/assets/8470b8ce-40b4-4b6c-839c-86b3887f4844)

---

## 1. Creating the Scan in Tenable

**First, we navigate to the scan creation page in Tenable:**

![1-In Tenable we are going to create a scan](https://github.com/user-attachments/assets/cb48323e-e1d1-4f65-9c7a-a343b1289f2b)

**Select the “Host Discovery” scan template:**

![2- Select Host Discovery Scan](https://github.com/user-attachments/assets/5b06a698-fb69-4320-ada9-56daca7066bb)

---

## 2. Identify Subnet Target in Azure

**In the Azure portal, navigate to the “Virtual Networks” section:**

![3- In Azure go to virtual networks](https://github.com/user-attachments/assets/cb4e1b5a-7b1e-4270-b42b-a7d946d44ed9)

**Locate the specific subnet of your virtual network to scan:**

![4- Copied the Subnet of the Virtual Network from my company](https://github.com/user-attachments/assets/1e03e043-e32b-4e0a-a99b-bf8aff73cde5)

---

## 3. Configuring the Scan in Tenable

**Back in Tenable, edit the scan and name it appropriately:**

![5- Editing and Naming the Scan](https://github.com/user-attachments/assets/4ccd1310-3f77-4bb7-af06-c7f72e708781)

**Paste the subnet CIDR block (e.g., `10.0.0.0/21`) into the “Targets” section:**

![6- Pasting the Subnet in the Target space](https://github.com/user-attachments/assets/cc241520-fd88-45bd-9e26-7823152c9121)

**Save and launch the scan:**

![7- Saved and Launched Scan](https://github.com/user-attachments/assets/adfebc7f-613f-483c-ad49-f509527aa814)

---

## 4. Scan Progress and Results

**The scan starts running and progress can be seen in Tenable:**

![8- Scan In Process](https://github.com/user-attachments/assets/f20f6fab-6dba-4eb5-9257-3d5bb96e4aef)

---

## Project Summary

This project showcases how to:

✅ Locate a subnet in Azure  
✅ Create a **Host Discovery Scan** in Tenable  
✅ Enter the subnet range as the target  
✅ Launch the scan and view real-time progress  

It’s an essential procedure to identify live hosts within an Azure environment and ensure that all hosts are accounted for during subsequent vulnerability assessments.

---

**Note**: Adjust the `./image-filename.png` paths to match your GitHub repository structure. Let me know if you’d like me to create a complete `README.md` file or push this to a GitHub repo!

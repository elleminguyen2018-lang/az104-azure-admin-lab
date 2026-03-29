# Azure AZ-104 Admin Lab

This is a beginner Azure AZ-104 lab where I built a small production style environment to practice core administrator skills.

---

## Architecture

![Architecture](architecture/az104-lab-diagram.png)

---

## What I built

* Microsoft Entra ID (Users, Groups, RBAC)
* Virtual Network with segmented subnets
* Management VM (jump host)
* Workload VM (private subnet)
* Network Security Group (NSG)
* Azure Monitor alert (CPU > 80%)
* Budget alert for cost control
* Azure Storage (Blob + File share)

---

## Screenshots

### Resource Group

![RG](screenshots/01-resource-group.png)

### RBAC (Entra ID Groups)

![RBAC](screenshots/02-rbac.png)

### Virtual Network & Subnets

![VNet](screenshots/03-vnet-subnets.png)

### Network Security Group

![NSG](screenshots/04-nsg.png)

### Virtual Machines

![VMs](screenshots/05-vms.png)

### Storage Account

![Storage](screenshots/06-storage.png)

### Monitor Alert (CPU > 80%)

![Alert](screenshots/07-monitor-alert.png)

### Budget Alert

![Budget](screenshots/08-budget.png)

---

## 📁 Project Structure

```
az104-azure-admin-lab/
├── README.md
├── architecture/
│   └── az104-lab-diagram.png
├── screenshots/
│   ├── 01-resource-group.png
│   ├── 02-rbac.png
│   ├── 03-vnet-subnets.png
│   ├── 04-nsg.png
│   ├── 05-vms.png
│   ├── 06-storage.png
│   ├── 07-monitor-alert.png
│   └── 08-budget.png
└── docs/
    ├── project-overview.md
    ├── deployment-steps.md
    └── lessons-learned.md
```

---

## 🎯 Key Learnings

* How to structure Azure resources in a production-style setup
* Importance of network segmentation (management vs workload)
* Using NSG rules to control access
* Monitoring resources with Azure Monitor
* Managing cost using Azure budgets

---

## 🚀 Notes

This is a beginner project as I continue learning Azure and cloud infrastructure.


az104-azure-admin-lab/
├── README.md
├── architecture/
│   └── az104-lab-diagram.png
├── screenshots/
│   ├── 01-resource-group.png
│   ├── 02-rbac.png
│   ├── 03-vnet-subnets.png
│   ├── 04-nsg.png
│   ├── 05-vms.png
│   ├── 06-storage.png
│   ├── 07-monitor-alert.png
│   └── 08-budget.png
└── docs/
    ├── project-overview.md
    ├── deployment-steps.md
    └── lessons-learned.md

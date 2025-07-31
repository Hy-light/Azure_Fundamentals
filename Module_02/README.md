# 🌐 Azure Fundamentals – Module 2: Azure Basics

🎯 **Objective:**  
Gain a clear understanding of the Azure ecosystem, its structure, and core components—so you can confidently navigate the Azure Portal, deploy resources, and understand the building blocks behind cloud services.

---

## 🏠 Azure Portal Tour

The **Azure Portal** is your web-based dashboard for managing everything in Azure.  
It’s where you:
- Create and manage virtual machines, web apps, databases, and storage
- Monitor resources and performance
- Set up security, billing, and user access

> 🧭 Think of it like a **control panel** for all your cloud services.

Key features:
- Search bar for quick access to services
- Dashboard customization (like widgets for your cloud)
- Access to tutorials, settings, and marketplace

🔗 Try it: [https://portal.azure.com](https://portal.azure.com)

---

## 🔑 Core Concepts

Understanding how Azure is structured geographically helps you make smart decisions about performance, availability, and compliance.

- **Regions:**  
  Physical locations (e.g., *East US*, *West Europe*) where Azure data centers live. You choose a region when deploying resources.

- **Geographies (Geos):**  
  Larger groupings of regions, often based on compliance or legal requirements (e.g., *Europe*, *Asia Pacific*).

- **Data Centers:**  
  The actual buildings where your data lives. Managed and secured by Microsoft.

> 📦 Choose regions close to your users for better performance.

---

## 🗂️ Azure Resource Hierarchy

Everything you create in Azure is organized within a **logical structure**. Think of it like folders within folders:

1. **Tenant** (your Microsoft identity environment, e.g., company or organization)
2. **Subscription** (billing container for your resources)
3. **Resource Group** (a logical grouping of related resources)
4. **Resources** (the actual services: VMs, storage, apps, etc.)

Example:

```
    Tenant: Contoso Ltd
    └── Subscription: Contoso Dev/Test
    └── Resource Group: WebAppRG
    ├── App Service: HelloWorldApp
    ├── Storage Account: contosostorage
    └── Database: contosodb
```

> 📌 Grouping resources helps you manage, monitor, and delete things more efficiently.

---

## 🎮 Hands-On Lab: Deploy a "Hello Cloud" Webpage

No code? No problem.

### Goal: Deploy a static HTML webpage using Azure App Service

#### Steps:
1. Log in to [Azure Portal](https://portal.azure.com)
2. Search for **"App Service"** and click *Create*
3. Choose:
   - Runtime: HTML
   - Region: Closest to you
   - App name: `hello-cloud-demo`
4. Review and *Create*
5. Once deployed, open the URL – and boom, you're in the cloud!

📝 Tip: You just created a **PaaS** (Platform as a Service) app in a few clicks!

---

## ❓ Quiz Time

Let’s see what you remember! (Sample questions below)

1. **Which Azure component is responsible for billing?**  
   A) Tenant  
   B) Resource Group  
   C) Subscription ✅  
   D) App Service

2. **What’s the best region to choose when creating resources?**  
   A) The one farthest away  
   B) The one closest to your users ✅  
   C) Any random one  
   D) Europe Central (always!)

3. **What’s the hierarchy level just above Resources?**  
   A) Azure Region  
   B) Subscription  
   C) Resource Group ✅  
   D) App Plan

---

## ✅ Summary

At this point you should be able to:
- Navigate the Azure Portal confidently
- Understand core cloud location concepts (Regions, Geos)
- Describe Azure’s resource hierarchy
- Deploy your first no-code web app in the cloud

🎉 You’ve taken your first real step inside the Azure universe!

---

### 👇 Next Step

We shall dive into Module three

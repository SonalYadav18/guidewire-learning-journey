# 🏗️ Guidewire Application Architecture & Integration Overview

This note outlines how the base Guidewire application is **customized** and **integrated** based on business needs.

---

## 🛠️ Customization Layers

Guidewire follows a **three-tier architecture**. Each tier can be extended or customized:

| Tier | Description | Examples |
|------|-------------|----------|
| **Data Tier** | Deals with persistence and data modeling | Entities, TypeLists |
| **Application Tier** | Business logic layer written in Gosu | Gosu Classes, Validation Rules |
| **Presentation Tier** | User Interface built using PCF files | PCF Screens, Widgets, InputSets |

> 🔧 Customization means modifying these layers to reflect the insurance company’s business model (products, rules, screens, etc.)

---

## 🔗 Integration Overview

Guidewire supports multiple integration methods to communicate with external systems (e.g., PolicyCenter, CRM, Payment Systems).

### 1. **Messaging**
- Asynchronous communication
- Typically uses JMS/XML
- Used for sending out claim updates, policy events, etc.

### 2. **Web Services**
- Real-time interaction via SOAP/REST
- Example: Retrieve or update information about a contact, policy, or claim

### 3. **Batch Processes**
- Scheduled tasks
- Used for background jobs (e.g., nightly reconciliation, report generation)

### 4. **Plugins**
- Custom Gosu classes to extend functionality
- Example: Claim Number Generator, Custom Underwriting Rules, Address Normalization

---

## 🧠 Summary

| Area | Focus |
|------|-------|
| Customization | Tailors the system to match business rules and processes |
| Integration | Enables communication with external systems and data sources |

Each tier and integration point is extensible through **Guidewire Studio**, using **Gosu**, **PCF**, and **XML configuration files**.


# 🖥️ Guidewire – PCF Basics

## 📌 What are PCF Files?
PCF in guidewire is. file format used to define the layout and behaviour of a specific page or section within the insuarnce application 
PCF (Page Configuration Files) are XML-like files used to design the UI in ClaimCenter.
PCF files support data binding, meaning UI fields can directly display or update values from the data model (entities, typelists, etc.). This enables real-time synchronization between the UI and backend.
They also support conditional logic, such as hiding or showing UI elements based on user roles or field values.

## 🔧 Common Widget Types

| Type        | Description             |
|-------------|--------------------------|
| `TextInput` | For single-line text fields |
| `DateInput` | For date fields |
| `SelectInput` | For dropdowns |
| `ListView`  | For tables/lists |
| `InputSet`  | For grouping related fields |
| `DetailView` | For full object forms |

### 🔸 1. Atomic Widgets (Basic UI Elements)
- **TextInput** – Text boxes
- **DateInput** – Date picker
- **CheckBox** – Yes/No fields
- **SelectInput** – Dropdown lists
- **RadioButton** – Single-choice options

### 🔸 2. Container Widgets
- **InputSet** – Group of related fields (e.g., address set)
- **ListView** – Table for listing records (e.g., claims, policies)
- **DetailView** – Full view of an entity
- **Toolbar** – Buttons or actions for the screen


## 💡 Sample Field (Dropdown)
```xml
<SelectInput id="IncidentSeverity"
             label="Incident Severity"
             value="Claim.IncidentSeverity"
             required="true"/>

## source
https://www.scribd.com/document/639429936/PCF-Introduction
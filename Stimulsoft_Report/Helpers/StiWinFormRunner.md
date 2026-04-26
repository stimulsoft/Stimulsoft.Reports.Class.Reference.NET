---
title: "StiWinFormRunner Class"
---

## StiWinFormRunner Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Inheritance

Implements: [IStiFormRunner](IStiFormRunner.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **OwnerWindow** | object |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** *(+1 overloads)* | void |  |
| **Dispose** | void |  |
| **ShowDialog** | void |  |

---

### Method Details

#### Create

**Create**(**formType**: string, **assemblyName**: string): void

**Parameters**

- **formType** (string)  
- **assemblyName** (string)  

---

**Create**(**formType**: string, **assemblyName**: string, ****: objectargs): void

**Parameters**

- **formType** (string)  
- **assemblyName** (string)  
- **** (objectargs)  


---

#### Dispose

**Dispose**(): void


---

#### ShowDialog

**ShowDialog**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Complete** | StiShowDialogCompleteEventHandler |  |

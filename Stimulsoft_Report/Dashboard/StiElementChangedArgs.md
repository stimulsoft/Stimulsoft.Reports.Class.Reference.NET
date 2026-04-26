---
title: "StiElementChangedArgs Class"
---

## StiElementChangedArgs Class

**Namespace:** `Stimulsoft.Report.Dashboard`

### Inheritance

Inherits from: EventArgs  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Action** | [StiElementMeterAction](StiElementMeterAction.md) |  |
| **NewName** | string |  |
| **OldName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateClearingAllArgs** `static` | [StiElementChangedArgs](StiElementChangedArgs.md) |  |
| **CreateDeletingArgs** `static` | [StiElementChangedArgs](StiElementChangedArgs.md) |  |
| **CreateEmptyArgs** `static` | [StiElementChangedArgs](StiElementChangedArgs.md) |  |
| **CreateRenamingArgs** `static` | [StiElementChangedArgs](StiElementChangedArgs.md) |  |

---

### Method Details

#### CreateClearingAllArgs `static`

**CreateClearingAllArgs**(): [StiElementChangedArgs](StiElementChangedArgs.md)

**Returns** [StiElementChangedArgs](StiElementChangedArgs.md)


---

#### CreateDeletingArgs `static`

**CreateDeletingArgs**(**name**: string): [StiElementChangedArgs](StiElementChangedArgs.md)

**Parameters**

- **name** (string)  

**Returns** [StiElementChangedArgs](StiElementChangedArgs.md)


---

#### CreateEmptyArgs `static`

**CreateEmptyArgs**(): [StiElementChangedArgs](StiElementChangedArgs.md)

**Returns** [StiElementChangedArgs](StiElementChangedArgs.md)


---

#### CreateRenamingArgs `static`

**CreateRenamingArgs**(**oldName**: string, **newName**: string): [StiElementChangedArgs](StiElementChangedArgs.md)

**Parameters**

- **oldName** (string)  
- **newName** (string)  

**Returns** [StiElementChangedArgs](StiElementChangedArgs.md)


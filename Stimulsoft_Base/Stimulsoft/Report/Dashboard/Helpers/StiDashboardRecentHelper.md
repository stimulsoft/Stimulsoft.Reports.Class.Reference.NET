---
title: "StiDashboardRecentHelper Class"
---

## StiDashboardRecentHelper Class

**Namespace:** `Stimulsoft.Report.Dashboard.Helpers`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DbsFiles** | List<string> |  |
| **ReportFile** | List<string> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` *(+1 overloads)* | void |  |
| **ContainsDbs** `static` | bool |  |
| **ContainsFile** `static` | bool |  |
| **Remove** `static` | void |  |
| **Save** `static` | bool |  |

---

### Method Details

#### Add `static`

**Add**(**containsDashboards**: bool, **path**: string, **autoSave**: bool): void

**Parameters**

- **containsDashboards** (bool)  
- **path** (string)  
- **autoSave** (bool)  

---

**Add**(**path**: string, **autoSave**: bool): void

**Parameters**

- **path** (string)  
- **autoSave** (bool)  


---

#### ContainsDbs `static`

**ContainsDbs**(**path**: string): bool

**Parameters**

- **path** (string)  

**Returns** bool


---

#### ContainsFile `static`

**ContainsFile**(**path**: string): bool

**Parameters**

- **path** (string)  

**Returns** bool


---

#### Remove `static`

**Remove**(**path**: string): void

**Parameters**

- **path** (string)  


---

#### Save `static`

**Save**(): bool

**Returns** bool


---
title: "StiReportsCollection Class"
---

## StiReportsCollection Class

**Namespace:** `Stimulsoft.Report`

Class describes a collection of reports. This collection used in SubReports property of StiReport.

### Inheritance

Inherits from: CollectionBase  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** *(+1 overloads)* | void |  |
| **AddRange** *(+1 overloads)* | void |  |
| **Contains** | bool |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Remove** | void |  |

---

### Method Details

#### Add

**Add**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  

---

**Add**(**report**: [StiReport](StiReport.md), **resetPageNumber**: bool, **printOnPreviousPage**: bool): void

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **resetPageNumber** (bool)  
- **printOnPreviousPage** (bool)  


---

#### AddRange

**AddRange**(**reports**: [StiReportsCollection](StiReportsCollection.md)): void

**Parameters**

- **reports** ([StiReportsCollection](StiReportsCollection.md))  

---

**AddRange**(****: StiReportreports): void

**Parameters**

- **** (StiReportreports)  


---

#### Contains

**Contains**(**report**: [StiReport](StiReport.md)): bool

**Parameters**

- **report** ([StiReport](StiReport.md))  

**Returns** bool


---

#### IndexOf

**IndexOf**(**report**: [StiReport](StiReport.md)): int

**Parameters**

- **report** ([StiReport](StiReport.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **report**: [StiReport](StiReport.md)): void

**Parameters**

- **index** (int)  
- **report** ([StiReport](StiReport.md))  


---

#### Remove

**Remove**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


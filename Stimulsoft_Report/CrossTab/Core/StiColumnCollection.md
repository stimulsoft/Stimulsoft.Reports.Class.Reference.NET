---
title: "StiColumnCollection Class"
---

## StiColumnCollection Class

**Namespace:** `Stimulsoft.Report.CrossTab.Core`

### Inheritance

Inherits from: CollectionBase  
Implements: IComparer  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** *(+1 overloads)* | void |  |
| **Clear** | void |  |
| **Insert** | void |  |
| **Sort** | void |  |
| **ToList** | List<[StiColumn](StiColumn.md)> |  |

---

### Method Details

#### Add

**Add**(**value**: object, **displayValue**: object): void

**Parameters**

- **value** (object)  
- **displayValue** (object)  

---

**Add**(**col**: [StiColumn](StiColumn.md)): void

**Parameters**

- **col** ([StiColumn](StiColumn.md))  


---

#### Clear

**Clear**(): void


---

#### Insert

**Insert**(**position**: int, **value**: object): void

**Parameters**

- **position** (int)  
- **value** (object)  


---

#### Sort

**Sort**(**direction**: [StiSortDirection](StiSortDirection.md), **sortType**: [StiSortType](StiSortType.md)): void

**Parameters**

- **direction** ([StiSortDirection](StiSortDirection.md))  
- **sortType** ([StiSortType](StiSortType.md))  


---

#### ToList

**ToList**(): List<[StiColumn](StiColumn.md)>

**Returns** List<[StiColumn](StiColumn.md)>


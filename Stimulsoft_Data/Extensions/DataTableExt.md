---
title: "DataTableExt Class"
---

## DataTableExt Class

**Namespace:** `Stimulsoft.Data.Extensions`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AsEnumerableArray** `static` | IEnumerable<object[]> |  |
| **ChildRelationList** `static` | IEnumerable<DataRelation> |  |
| **GetUniqueName** `static` *(+2 overloads)* | string |  |
| **ParentRelationList** `static` | IEnumerable<DataRelation> |  |

---

### Method Details

#### AsEnumerableArray `static`

**AsEnumerableArray**(**joinedTable**: DataTable): IEnumerable<object[]>

**Parameters**

- **joinedTable** (DataTable)  

**Returns** IEnumerable<object[]>


---

#### ChildRelationList `static`

**ChildRelationList**(**table**: DataTable): IEnumerable<DataRelation>

**Parameters**

- **table** (DataTable)  

**Returns** IEnumerable<DataRelation>


---

#### GetUniqueName `static`

**GetUniqueName**(**table**: DataTable, **meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)): string

**Parameters**

- **table** (DataTable)  
- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

**Returns** string

---

**GetUniqueName**(**table**: DataTable, **meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md), **baseName**: string): string

**Parameters**

- **table** (DataTable)  
- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  
- **baseName** (string)  

**Returns** string

---

**GetUniqueName**(**table**: DataTable, **baseName**: string): string

**Parameters**

- **table** (DataTable)  
- **baseName** (string)  

**Returns** string


---

#### ParentRelationList `static`

**ParentRelationList**(**table**: DataTable): IEnumerable<DataRelation>

**Parameters**

- **table** (DataTable)  

**Returns** IEnumerable<DataRelation>


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **NullTable** | DataTable |  |

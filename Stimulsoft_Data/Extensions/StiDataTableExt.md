---
title: "StiDataTableExt Class"
---

## StiDataTableExt Class

**Namespace:** `Stimulsoft.Data.Extensions`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddColumn** `static` | DataColumn |  |
| **ColumnsList** `static` | List<DataColumn> |  |
| **Remove** `static` *(+1 overloads)* | DataTable |  |

---

### Method Details

#### AddColumn `static`

**AddColumn**(**table**: DataTable, **column**: DataColumn, **order**: int): DataColumn

**Parameters**

- **table** (DataTable)  
- **column** (DataColumn)  
- **order** (int)  

**Returns** DataColumn


---

#### ColumnsList `static`

**ColumnsList**(**table**: DataTable): List<DataColumn>

**Parameters**

- **table** (DataTable)  

**Returns** List<DataColumn>


---

#### Remove `static`

**Remove**(**table**: DataTable, **columns**: IEnumerable<DataColumn>): DataTable

**Parameters**

- **table** (DataTable)  
- **columns** (IEnumerable<DataColumn>)  

**Returns** DataTable

---

**Remove**(**table**: DataTable, **columns**: IEnumerable<string>): DataTable

**Parameters**

- **table** (DataTable)  
- **columns** (IEnumerable<string>)  

**Returns** DataTable


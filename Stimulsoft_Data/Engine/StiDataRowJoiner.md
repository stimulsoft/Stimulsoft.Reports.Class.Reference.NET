---
title: "StiDataRowJoiner Class"
---

## StiDataRowJoiner Class

**Namespace:** `Stimulsoft.Data.Engine`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataRowJoiner**(DataTable resultTable, DataTable table1, DataTable table2) | While this instance is used, 's columns (their number, types, names and order) MUST NOT be changed. |

**StiDataRowJoiner**(**resultTable**: DataTable, **table1**: DataTable, **table2**: DataTable)

While this instance is used, 's columns (their number, types, names and order) MUST NOT be changed.

**Parameters**

- **resultTable** (DataTable)  
- **table1** (DataTable)  
- **table2** (DataTable)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **Join** | IEnumerable<DataRow> |  |

---

### Method Details

#### Equals

**Equals**(**x**: StringKey, **y**: StringKey): bool

**Parameters**

- **x** (StringKey)  
- **y** (StringKey)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(**obj**: StringKey): int

**Parameters**

- **obj** (StringKey)  

**Returns** int


---

#### Join

**Join**(**type**: [StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md), **link**: [StiDataLink](StiDataLink.md), **meters**: IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>): IEnumerable<DataRow>

**Parameters**

- **type** ([StiDataJoinType](../../Stimulsoft_Base/root/StiDataJoinType.md))  
- **link** ([StiDataLink](StiDataLink.md))  
- **meters** (IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  

**Returns** IEnumerable<DataRow>


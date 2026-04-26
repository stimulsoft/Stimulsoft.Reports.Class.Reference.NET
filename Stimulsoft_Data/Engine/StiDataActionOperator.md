---
title: "StiDataActionOperator Class"
---

## StiDataActionOperator Class

**Namespace:** `Stimulsoft.Data.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyAfterGrouping** `static` | [StiDataTable](StiDataTable.md) |  |
| **ApplyBeforeGrouping** `static` | DataTable |  |

---

### Method Details

#### ApplyAfterGrouping `static`

**ApplyAfterGrouping**(**inTable**: [StiDataTable](StiDataTable.md), **actions**: IEnumerable<StiDataActionRule>, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **hash**: int): [StiDataTable](StiDataTable.md)

**Parameters**

- **inTable** ([StiDataTable](StiDataTable.md))  
- **actions** (IEnumerable<StiDataActionRule>)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **hash** (int)  

**Returns** [StiDataTable](StiDataTable.md)


---

#### ApplyBeforeGrouping `static`

**ApplyBeforeGrouping**(**inTable**: DataTable, **actions**: IEnumerable<StiDataActionRule>, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md), **hash**: int): DataTable

**Parameters**

- **inTable** (DataTable)  
- **actions** (IEnumerable<StiDataActionRule>)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  
- **hash** (int)  

**Returns** DataTable


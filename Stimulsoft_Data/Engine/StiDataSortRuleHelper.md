---
title: "StiDataSortRuleHelper Class"
---

## StiDataSortRuleHelper Class

**Namespace:** `Stimulsoft.Data.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetSortDirection** `static` | [StiDataSortDirection](StiDataSortDirection.md) |  |
| **SetSortDirection** `static` | List<StiDataSortRule> |  |
| **ToList** `static` | List<StiDataSortRule> | Used in the CodeDom report compiler. |

---

### Method Details

#### GetSortDirection `static`

**GetSortDirection**(**rules**: List<StiDataSortRule>, **columnKey**: string): [StiDataSortDirection](StiDataSortDirection.md)

**Parameters**

- **rules** (List<StiDataSortRule>)  
- **columnKey** (string)  

**Returns** [StiDataSortDirection](StiDataSortDirection.md)


---

#### SetSortDirection `static`

**SetSortDirection**(**rules**: List<StiDataSortRule>, **columnKeys**: List<string>, **columnKey**: string, **direction**: [StiDataSortDirection](StiDataSortDirection.md)): List<StiDataSortRule>

**Parameters**

- **rules** (List<StiDataSortRule>)  
- **columnKeys** (List<string>)  
- **columnKey** (string)  
- **direction** ([StiDataSortDirection](StiDataSortDirection.md))  

**Returns** List<StiDataSortRule>


---

#### ToList `static`

**ToList**(****: StiDataSortRulerules): List<StiDataSortRule>

Used in the CodeDom report compiler.

**Parameters**

- **** (StiDataSortRulerules)  

**Returns** List<StiDataSortRule>


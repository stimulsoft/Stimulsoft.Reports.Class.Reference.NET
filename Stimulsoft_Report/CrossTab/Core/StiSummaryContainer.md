---
title: "StiSummaryContainer Class"
---

## StiSummaryContainer Class

**Namespace:** `Stimulsoft.Report.CrossTab.Core`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSummaryContainer**(int level) |  |

**StiSummaryContainer**(**level**: int)

**Parameters**

- **level** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetArguments** | Hashtable |  |
| **GetDataCol** | Hashtable |  |
| **GetSummary** | [StiSummary](StiSummary.md) |  |

---

### Method Details

#### GetArguments

**GetArguments**(**argValues**: Hashtable): Hashtable

**Parameters**

- **argValues** (Hashtable)  

**Returns** Hashtable


---

#### GetDataCol

**GetDataCol**(): Hashtable

**Returns** Hashtable


---

#### GetSummary

**GetSummary**(**col**: [StiColumn](StiColumn.md), **row**: [StiRow](../../Dictionary/StiRow.md), **create**: bool): [StiSummary](StiSummary.md)

**Parameters**

- **col** ([StiColumn](StiColumn.md))  
- **row** ([StiRow](../../Dictionary/StiRow.md))  
- **create** (bool)  

**Returns** [StiSummary](StiSummary.md)


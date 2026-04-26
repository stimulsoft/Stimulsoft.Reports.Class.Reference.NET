---
title: "StiDataHelper Class"
---

## StiDataHelper Class

**Namespace:** `Stimulsoft.Report.Components`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFilterEventHandler** `static` | object |  |
| **GetFilterExpression** `static` | string |  |
| **SetData** `static` *(+1 overloads)* | void |  |

---

### Method Details

#### GetFilterEventHandler `static`

**GetFilterEventHandler**(**component**: StiComponent, **dataSource**: object): object

**Parameters**

- **component** (StiComponent)  
- **dataSource** (object)  

**Returns** object


---

#### GetFilterExpression `static`

**GetFilterExpression**(**filter**: StiFilter, **fullColumnName**: string, **report**: [StiReport](../root/StiReport.md)): string

**Parameters**

- **filter** (StiFilter)  
- **fullColumnName** (string)  
- **report** ([StiReport](../root/StiReport.md))  

**Returns** string


---

#### SetData `static`

**SetData**(**component**: StiComponent, **reinit**: bool): void

**Parameters**

- **component** (StiComponent)  
- **reinit** (bool)  

---

**SetData**(**component**: StiComponent, **reinit**: bool, **masterComponent**: StiComponent, **allowReconnectOnEachRow**: bool): void

**Parameters**

- **component** (StiComponent)  
- **reinit** (bool)  
- **masterComponent** (StiComponent)  
- **allowReconnectOnEachRow** (bool)  


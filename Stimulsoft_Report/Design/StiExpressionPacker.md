---
title: "StiExpressionPacker Class"
---

## StiExpressionPacker Class

**Namespace:** `Stimulsoft.Report.Design`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCorrectedAlias** `static` | string |  |
| **PackExpression** `static` *(+1 overloads)* | string |  |
| **UnPackExpression** `static` *(+1 overloads)* | string |  |

---

### Method Details

#### GetCorrectedAlias `static`

**GetCorrectedAlias**(**alias**: string): string

**Parameters**

- **alias** (string)  

**Returns** string


---

#### PackExpression `static`

**PackExpression**(**expressionStr**: string, **designer**: [IStiDesignerBase](IStiDesignerBase.md), **useBraces**: bool): string

**Parameters**

- **expressionStr** (string)  
- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **useBraces** (bool)  

**Returns** string

---

**PackExpression**(**expressionStr**: string, **report**: [StiReport](../root/StiReport.md), **useBraces**: bool): string

**Parameters**

- **expressionStr** (string)  
- **report** ([StiReport](../root/StiReport.md))  
- **useBraces** (bool)  

**Returns** string


---

#### UnPackExpression `static`

**UnPackExpression**(**expressionStr**: string, **designer**: [IStiDesignerBase](IStiDesignerBase.md), **useBraces**: bool): string

**Parameters**

- **expressionStr** (string)  
- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **useBraces** (bool)  

**Returns** string

---

**UnPackExpression**(**expressionStr**: string, **report**: [StiReport](../root/StiReport.md), **useBraces**: bool): string

**Parameters**

- **expressionStr** (string)  
- **report** ([StiReport](../root/StiReport.md))  
- **useBraces** (bool)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **First** | string |  |
| **Second** | string |  |

---
title: "StiCrossValueExpression Class"
---

## StiCrossValueExpression Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiExpression  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCrossValueExpression**() | Creates a new expression. |
| **StiCrossValueExpression**(string value) | Creates a new expression. |

**StiCrossValueExpression**()

Creates a new expression.

---

**StiCrossValueExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string) — Expression value.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Returns the event for processing of the expression while script report generation. |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): StiEvent

Returns the event for processing of the expression while script report generation.

**Returns** StiEvent — The event to process the expression.


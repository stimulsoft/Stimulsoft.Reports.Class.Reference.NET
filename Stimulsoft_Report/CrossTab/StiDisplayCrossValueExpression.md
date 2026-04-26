---
title: "StiDisplayCrossValueExpression Class"
---

## StiDisplayCrossValueExpression Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiExpression  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDisplayCrossValueExpression**() | Creates a new expression. |
| **StiDisplayCrossValueExpression**(string value) | Creates a new expression. |

**StiDisplayCrossValueExpression**()

Creates a new expression.

---

**StiDisplayCrossValueExpression**(**value**: string)

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


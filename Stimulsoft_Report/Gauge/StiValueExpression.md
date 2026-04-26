---
title: "StiValueExpression Class"
---

## StiValueExpression Class

**Namespace:** `Stimulsoft.Report.Gauge`

### Inheritance

Inherits from: StiExpression  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiValueExpression**() | Creates a new expression. |
| **StiValueExpression**(string value) | Creates a new expression. |

**StiValueExpression**()

Creates a new expression.

---

**StiValueExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | Stimulsoft.Report.Events.StiEvent | Returns the event for processing of the expression while script report generation. |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): Stimulsoft.Report.Events.StiEvent

Returns the event for processing of the expression while script report generation.

**Returns** Stimulsoft.Report.Events.StiEvent — The event to process the expression.


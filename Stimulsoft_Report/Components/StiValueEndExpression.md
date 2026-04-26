---
title: "StiValueEndExpression Class"
---

## StiValueEndExpression Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiExpression  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiValueEndExpression**() | Creates a new expression. |
| **StiValueEndExpression**(string value) | Creates a new expression. |

**StiValueEndExpression**()

Creates a new expression.

---

**StiValueEndExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string) — Expression value.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Returns the event for processing of the expession when generation the report script. |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): StiEvent

Returns the event for processing of the expession when generation the report script.

**Returns** StiEvent — The event for processing of the expession.


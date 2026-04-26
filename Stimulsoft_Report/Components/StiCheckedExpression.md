---
title: "StiCheckedExpression Class"
---

## StiCheckedExpression Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiUnifiedExpression](StiUnifiedExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCheckedExpression**() | Creates a new expression. |
| **StiCheckedExpression**(string value) | Creates a new expression. |
| **StiCheckedExpression**(StiComponent parent, string propertyName) | Creates a new expression. |

**StiCheckedExpression**()

Creates a new expression.

---

**StiCheckedExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string) — Expression value.  

---

**StiCheckedExpression**(**parent**: StiComponent, **propertyName**: string)

Creates a new expression.

**Parameters**

- **parent** (StiComponent)  
- **propertyName** (string)  


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


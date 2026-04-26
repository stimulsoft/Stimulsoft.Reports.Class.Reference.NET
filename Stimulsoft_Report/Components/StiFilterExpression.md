---
title: "StiFilterExpression Class"
---

## StiFilterExpression Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiUnifiedExpression](StiUnifiedExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFilterExpression**() | Creates a new expression. |
| **StiFilterExpression**(string value) | Creates a new expression. |
| **StiFilterExpression**(StiComponent parent, string propertyName) | Creates a new expression. |

**StiFilterExpression**()

Creates a new expression.

---

**StiFilterExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string) — Expression value.  

---

**StiFilterExpression**(**parent**: StiComponent, **propertyName**: string)

Creates a new expression.

**Parameters**

- **parent** (StiComponent)  
- **propertyName** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Returns the event for generation of the expression when report script generation. |

---

### Method Details

#### GetDefaultEvent

**GetDefaultEvent**(): StiEvent

Returns the event for generation of the expression when report script generation.

**Returns** StiEvent — The event for processing of the expression.


---
title: "StiDataUrlExpression Class"
---

## StiDataUrlExpression Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiUnifiedExpression](StiUnifiedExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataUrlExpression**() | Creates a new expression. |
| **StiDataUrlExpression**(string value) | Creates a new expression. |
| **StiDataUrlExpression**(StiComponent parent, string propertyName) | Creates a new expression. |

**StiDataUrlExpression**()

Creates a new expression.

---

**StiDataUrlExpression**(**value**: string)

Creates a new expression.

**Parameters**

- **value** (string) — Expression value.  

---

**StiDataUrlExpression**(**parent**: StiComponent, **propertyName**: string)

Creates a new expression.

**Parameters**

- **parent** (StiComponent)  
- **propertyName** (string)  


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


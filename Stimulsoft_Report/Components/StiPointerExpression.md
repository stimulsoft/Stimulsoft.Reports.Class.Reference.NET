---
title: "StiPointerExpression Class"
---

## StiPointerExpression Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiUnifiedExpression](StiUnifiedExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPointerExpression**() | Creates a new expression. |
| **StiPointerExpression**(string val) | Creates a new expression. |
| **StiPointerExpression**(StiComponent parent, string propertyName) | Creates a new expression. |

**StiPointerExpression**()

Creates a new expression.

---

**StiPointerExpression**(**val**: string)

Creates a new expression.

**Parameters**

- **val** (string) — Expression value.  

---

**StiPointerExpression**(**parent**: StiComponent, **propertyName**: string)

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


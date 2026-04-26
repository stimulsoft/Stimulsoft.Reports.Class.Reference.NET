---
title: "Function Class"
---

## Function Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpression](LogicalExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Function**([Identifier](Identifier.md) identifier, LogicalExpressionexpressions ) |  |

**Function**(**identifier**: [Identifier](Identifier.md), ****: LogicalExpressionexpressions)

**Parameters**

- **identifier** ([Identifier](Identifier.md))  
- **** (LogicalExpressionexpressions)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expressions** | [LogicalExpression](LogicalExpression.md)[] |  |
| **Identifier** | [Identifier](Identifier.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Accept** | void |  |

---

### Method Details

#### Accept

**Accept**(**visitor**: [LogicalExpressionVisitor](LogicalExpressionVisitor.md)): void

**Parameters**

- **visitor** ([LogicalExpressionVisitor](LogicalExpressionVisitor.md))  


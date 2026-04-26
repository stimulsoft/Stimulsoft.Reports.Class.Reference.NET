---
title: "UnaryExpression Class"
---

## UnaryExpression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpression](LogicalExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **UnaryExpression**([UnaryExpressionType](UnaryExpressionType.md) type, [LogicalExpression](LogicalExpression.md) expression) |  |

**UnaryExpression**(**type**: [UnaryExpressionType](UnaryExpressionType.md), **expression**: [LogicalExpression](LogicalExpression.md))

**Parameters**

- **type** ([UnaryExpressionType](UnaryExpressionType.md))  
- **expression** ([LogicalExpression](LogicalExpression.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expression** | [LogicalExpression](LogicalExpression.md) |  |
| **Type** | [UnaryExpressionType](UnaryExpressionType.md) |  |

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


---
title: "TernaryExpression Class"
---

## TernaryExpression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpression](LogicalExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TernaryExpression**([LogicalExpression](LogicalExpression.md) leftExpression, [LogicalExpression](LogicalExpression.md) middleExpression, [LogicalExpression](LogicalExpression.md) rightExpression) |  |

**TernaryExpression**(**leftExpression**: [LogicalExpression](LogicalExpression.md), **middleExpression**: [LogicalExpression](LogicalExpression.md), **rightExpression**: [LogicalExpression](LogicalExpression.md))

**Parameters**

- **leftExpression** ([LogicalExpression](LogicalExpression.md))  
- **middleExpression** ([LogicalExpression](LogicalExpression.md))  
- **rightExpression** ([LogicalExpression](LogicalExpression.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LeftExpression** | [LogicalExpression](LogicalExpression.md) |  |
| **MiddleExpression** | [LogicalExpression](LogicalExpression.md) |  |
| **RightExpression** | [LogicalExpression](LogicalExpression.md) |  |

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


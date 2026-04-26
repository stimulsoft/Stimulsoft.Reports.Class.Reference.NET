---
title: "BinaryExpression Class"
---

## BinaryExpression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpression](LogicalExpression.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BinaryExpression**([BinaryExpressionType](BinaryExpressionType.md) type, [LogicalExpression](LogicalExpression.md) leftExpression, [LogicalExpression](LogicalExpression.md) rightExpression) |  |

**BinaryExpression**(**type**: [BinaryExpressionType](BinaryExpressionType.md), **leftExpression**: [LogicalExpression](LogicalExpression.md), **rightExpression**: [LogicalExpression](LogicalExpression.md))

**Parameters**

- **type** ([BinaryExpressionType](BinaryExpressionType.md))  
- **leftExpression** ([LogicalExpression](LogicalExpression.md))  
- **rightExpression** ([LogicalExpression](LogicalExpression.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LeftExpression** | [LogicalExpression](LogicalExpression.md) |  |
| **RightExpression** | [LogicalExpression](LogicalExpression.md) |  |
| **Type** | [BinaryExpressionType](BinaryExpressionType.md) |  |

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


---
title: "EvaluationVisitor Class"
---

## EvaluationVisitor Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc.Domain`

### Inheritance

Inherits from: [LogicalExpressionVisitor](LogicalExpressionVisitor.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **EvaluationVisitor**([EvaluateOptions](../EvaluateOptions.md) options) |  |

**EvaluationVisitor**(**options**: [EvaluateOptions](../EvaluateOptions.md))

**Parameters**

- **options** ([EvaluateOptions](../EvaluateOptions.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Result** | object |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CompareUsingMostPreciseType** | object |  |
| **Visit** *(+6 overloads)* | void |  |

---

### Method Details

#### CompareUsingMostPreciseType

**CompareUsingMostPreciseType**(**a**: object, **b**: object): object

**Parameters**

- **a** (object)  
- **b** (object)  

**Returns** object


---

#### Visit

**Visit**(**expression**: [LogicalExpression](LogicalExpression.md)): void

**Parameters**

- **expression** ([LogicalExpression](LogicalExpression.md))  

---

**Visit**(**expression**: [TernaryExpression](TernaryExpression.md)): void

**Parameters**

- **expression** ([TernaryExpression](TernaryExpression.md))  

---

**Visit**(**expression**: [BinaryExpression](BinaryExpression.md)): void

**Parameters**

- **expression** ([BinaryExpression](BinaryExpression.md))  

---

**Visit**(**expression**: [UnaryExpression](UnaryExpression.md)): void

**Parameters**

- **expression** ([UnaryExpression](UnaryExpression.md))  

---

**Visit**(**expression**: [ValueExpression](ValueExpression.md)): void

**Parameters**

- **expression** ([ValueExpression](ValueExpression.md))  

---

**Visit**(**function**: [Function](Function.md)): void

**Parameters**

- **function** ([Function](Function.md))  

---

**Visit**(**parameter**: [Identifier](Identifier.md)): void

**Parameters**

- **parameter** ([Identifier](Identifier.md))  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **EvaluateFunction** | EvaluateFunctionHandler |  |
| **EvaluateParameter** | EvaluateParameterHandler |  |

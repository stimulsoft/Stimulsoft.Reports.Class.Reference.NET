---
title: "Expression Class"
---

## Expression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc`

### Constructors

| Constructor | Description |
| --- | --- |
| **Expression**(string expression) |  |
| **Expression**([LogicalExpression](Domain/LogicalExpression.md) expression) |  |
| **Expression**(string expression, [EvaluateOptions](EvaluateOptions.md) options) |  |
| **Expression**([LogicalExpression](Domain/LogicalExpression.md) expression, [EvaluateOptions](EvaluateOptions.md) options) |  |

**Expression**(**expression**: string)

**Parameters**

- **expression** (string)  

---

**Expression**(**expression**: [LogicalExpression](Domain/LogicalExpression.md))

**Parameters**

- **expression** ([LogicalExpression](Domain/LogicalExpression.md))  

---

**Expression**(**expression**: string, **options**: [EvaluateOptions](EvaluateOptions.md))

**Parameters**

- **expression** (string)  
- **options** ([EvaluateOptions](EvaluateOptions.md))  

---

**Expression**(**expression**: [LogicalExpression](Domain/LogicalExpression.md), **options**: [EvaluateOptions](EvaluateOptions.md))

**Parameters**

- **expression** ([LogicalExpression](Domain/LogicalExpression.md))  
- **options** ([EvaluateOptions](EvaluateOptions.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Error** | string |  |
| **Options** | [EvaluateOptions](EvaluateOptions.md) |  |
| **ParsedExpression** | [LogicalExpression](Domain/LogicalExpression.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Compile** `static` | [LogicalExpression](Domain/LogicalExpression.md) |  |
| **Evaluate** | object |  |
| **HasErrors** | bool | Pre-compiles the expression in order to check syntax errors. If errors are detected, the Error property contains the message. |

---

### Method Details

#### Compile `static`

**Compile**(**expression**: string, **nocache**: bool): [LogicalExpression](Domain/LogicalExpression.md)

**Parameters**

- **expression** (string)  
- **nocache** (bool)  

**Returns** [LogicalExpression](Domain/LogicalExpression.md)


---

#### Evaluate

**Evaluate**(): object

**Returns** object


---

#### HasErrors

**HasErrors**(): bool

Pre-compiles the expression in order to check syntax errors. If errors are detected, the Error property contains the message.

**Returns** bool — True if the expression syntax is correct, otherwiser False


### Events

| Event | Type | Description |
| --- | --- | --- |
| **EvaluateFunction** | EvaluateFunctionHandler |  |
| **EvaluateParameter** | EvaluateParameterHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **OriginalExpression** | string | Textual representation of the expression to evaluate. |

---
title: "Expression Class"
---

## Expression Class

**Namespace:** `Stimulsoft.Data.Expressions.NCalc`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class Expression
```

### Constructors

| Constructor | Description |
| --- | --- |
| `Expression(string expression)` |  |
| `Expression([LogicalExpression](Domain/LogicalExpression.md) expression)` |  |
| `Expression(string expression, [EvaluateOptions](EvaluateOptions.md) options)` |  |
| `Expression([LogicalExpression](Domain/LogicalExpression.md) expression, [EvaluateOptions](EvaluateOptions.md) options)` |  |

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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **EvaluateFunction** | EvaluateFunctionHandler |  |
| **EvaluateParameter** | EvaluateParameterHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **OriginalExpression** | string | Textual representation of the expression to evaluate. |

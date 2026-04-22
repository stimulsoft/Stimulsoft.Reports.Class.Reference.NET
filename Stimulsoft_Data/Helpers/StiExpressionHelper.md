---
title: "StiExpressionHelper Class"
---

## StiExpressionHelper Class

**Namespace:** `Stimulsoft.Data.Helpers`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class StiExpressionHelper
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Compile** `static` | [LogicalExpression](../Expressions/NCalc/Domain/LogicalExpression.md) |  |
| **EscapeExpression** `static` | string |  |
| **FetchBlocksFromExpression** `static` | List<string> |  |
| **GetArguments** `static` | List<string> |  |
| **GetFirstArgumentFromExpression** `static` | string |  |
| **GetFunction** `static` | string |  |
| **IsAggregationFunctionPresent** `static` | bool |  |
| **IsExpression** `static` | bool |  |
| **IsFunctionPresent** `static` | bool |  |
| **IsPercentOfGrandTotal** `static` | bool |  |
| **IsThisExpression** `static` | bool |  |
| **IsTimeExpression** `static` | bool |  |
| **NewExpression** `static` | [Expression](../Expressions/NCalc/Expression.md) |  |
| **ParseReportExpression** `static` | string |  |
| **PrepareExpression** `static` | string |  |
| **RemoveFunction** `static` | string |  |
| **RemoveRelations** `static` | string |  |
| **ReplaceExpressionBlocksByValues** `static` | string |  |
| **ReplaceFunction** `static` | string |  |
| **Visit** *(+6 overloads)* | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Parameters** | HashSet<string> |  |

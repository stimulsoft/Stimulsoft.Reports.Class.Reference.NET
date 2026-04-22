---
title: "StiAppParser Class"
---

## StiAppParser Class

**Namespace:** `Stimulsoft.Report.App`  
**Assembly:** `Stimulsoft.Report`

```csharp
public static class StiAppParser
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UseScriptParser** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetExpressions** `static` | IEnumerable<StiAppExpression> |  |
| **IsDataPathExistInBindings** `static` | bool |  |
| **IsDataPathExistInExpression** `static` | bool |  |
| **IsVariablesExistInBindings** `static` | bool |  |
| **IsVariablesExistInExpression** `static` | bool |  |
| **ParseBoolExpression** `static` | bool |  |
| **ParseBoolExpressionOrDefault** `static` | bool |  |
| **ParseBrushExpression** `static` | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **ParseColorExpression** `static` | Color |  |
| **ParseColorExpressionOrDefault** `static` | Color |  |
| **ParseDecimalExpression** `static` | decimal |  |
| **ParseDecimalExpressionOrDefault** `static` | decimal |  |
| **ParseEnumExpression** `static` *(+1 overloads)* | T |  |
| **ParseEnumExpressionOrDefault** `static` | T |  |
| **ParseFloatExpression** `static` | float |  |
| **ParseFloatExpressionOrDefault** `static` | float |  |
| **ParseFontExpression** `static` | [Font](../../Stimulsoft_Drawing/Font.md) |  |
| **ParseFontExpressionOrDefault** `static` | [Font](../../Stimulsoft_Drawing/Font.md) |  |
| **ParseIntExpression** `static` | int |  |
| **ParseIntExpressionOrDefault** `static` | int |  |
| **ParseStringExpression** `static` | string |  |
| **ParseStringExpressionOrDefault** `static` | string |  |
| **ProcessExpressions** `static` | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ErrorTime** | DateTime |  |
| **Expr** | string |  |
| **Value** | object |  |

---
title: "StiScriptHelper Class"
---

## StiScriptHelper Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public static class StiScriptHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCaching** `static` | bool |  |
| **TokenPositions** | List<StiCSharpScriptParser.TokenPosition> |  |
| **Tokens** | List<[StiToken](../Stimulsoft_Base/StiToken.md)> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearCache** `static` | void |  |
| **ClearTokensCache** `static` | void |  |
| **ClearTypesCache** `static` | void |  |
| **ContainsFunction** | bool |  |
| **ContainsNestedObject** | bool |  |
| **ContainsObject** | bool |  |
| **GetNestedObject** | bool |  |
| **GetObject** | object |  |
| **InvokeEventScript** `static` | object |  |
| **InvokeFunction** | object |  |
| **InvokeTextExpression** `static` | string | Parses a mixed expression containing plain text and C# code blocks in curly braces. Each block in { } is executed as C# code, the rest is treated as plain text. Example: "Text {return 1+1;} more text {return DateTime.Now.Year;}" |
| **IsAllowScriptsToRun** `static` | bool |  |
| **IsEventScript** `static` | bool |  |
| **IsObjectSupportsNesting** | bool |  |
| **IsReadOnlyObject** | bool |  |
| **IsScriptInExpression** `static` *(+1 overloads)* | bool |  |
| **ParseTextValue** `static` *(+3 overloads)* | object |  |
| **SetObject** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **VariableChanged** | StiVariableChangedEventHandler |  |

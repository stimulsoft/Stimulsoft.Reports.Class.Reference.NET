---
title: "StiUserFunction Class"
---

## StiUserFunction Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiUserFunction
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiUserFunction()` | Creates an object of the type StiUserFunction. |
| `StiUserFunction(string name)` | Creates an object of the type StiUserFunction. |
| `StiUserFunction(string name, [StiFunctionCategory](StiFunctionCategory.md) category)` | Creates an object of the type StiUserFunction. |
| `StiUserFunction(string name, [StiFunctionCategory](StiFunctionCategory.md) category, [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md) returnType)` | Creates an object of the type StiUserFunction. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Arguments** | StiUserFunctionArgumentsCollection |  |
| **Category** | [StiFunctionCategory](StiFunctionCategory.md) |  |
| **CustomCategory** | string |  |
| **Description** | string |  |
| **Name** | string |  |
| **ReturnType** | [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md) |  |
| **ScriptBlockly** | string |  |
| **ScriptCSharp** | string |  |
| **ScriptJS** | string |  |
| **ScriptMode** | [StiFunctionScriptMode](StiFunctionScriptMode.md) |  |
| **ScriptVB** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetFullScript** | string |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

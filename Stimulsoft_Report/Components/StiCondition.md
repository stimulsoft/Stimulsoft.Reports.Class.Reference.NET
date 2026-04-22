---
title: "StiCondition Class"
---

## StiCondition Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCondition
```

### Inheritance

Inherits from: [StiBaseCondition](StiBaseCondition.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCondition**() | Creates a new object of the type StiCondition. |
| **StiCondition**(string expression, Color textColor, Color backColor, [Font](../../Stimulsoft_Drawing/Font.md) font, bool enabled) | Creates a new object of the type StiCondition. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AssignExpression** | string |  |
| **BackColor** | Color |  |
| **BreakIfTrue** | bool |  |
| **CanAssignExpression** | bool |  |
| **Enabled** | bool |  |
| **Font** | [Font](../../Stimulsoft_Drawing/Font.md) |  |
| **Icon** | byte[] |  |
| **IconSize** | Size? |  |
| **Permissions** | [StiConditionPermissions](StiConditionPermissions.md) |  |
| **Style** | string |  |
| **TextColor** | Color |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool |  |
| **GetFonts** | List<[StiFont](../../Stimulsoft_Base/StiFont.md)> |  |
| **GetHashCode** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IconAlignment** | ContentAlignment |  |

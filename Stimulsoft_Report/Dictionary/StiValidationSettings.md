---
title: "StiValidationSettings Class"
---

## StiValidationSettings Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiValidationSettings
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expression** | string |  |
| **ExpressionLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **ExpressionMessage** | string |  |
| **Max** | string |  |
| **Min** | string |  |
| **PatternLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **PatternMessage** | string |  |
| **PatternRegex** | string |  |
| **PatternType** | [StiValidationPatternType](StiValidationPatternType.md) |  |
| **RangeLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **RangeMessage** | string |  |
| **Required** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Parse** `static` | [StiValidationSettings](StiValidationSettings.md) |  |
| **ToString** `static` *(+1 overloads)* | string |  |
| **Validate** | [StiValidationResult](StiValidationResult.md) |  |

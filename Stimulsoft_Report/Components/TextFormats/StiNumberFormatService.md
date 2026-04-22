---
title: "StiNumberFormatService Class"
---

## StiNumberFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiNumberFormatService
```

### Inheritance

Inherits from: StiFormatService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiNumberFormatService()` | Creates a new format of the type StiNumberFormatService. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** *(+1 overloads)* | object |  |
| **CorrectNegativeZero** | object |  |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object in order of regulations and returns a string. |
| **GetHashCode** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **decimalDigits** | int |  |
| **decimalSeparator** | string |  |
| **groupSeparator** | string |  |
| **groupSize** | int |  |
| **negativePattern** | int |  |
| **nullDisplay** | string |  |
| **states** | [StiTextFormatState](../../../Stimulsoft_Dashboard/StiTextFormatState.md) |  |
| **useGroupSeparator** | bool |  |
| **useLocalSetting** | bool |  |

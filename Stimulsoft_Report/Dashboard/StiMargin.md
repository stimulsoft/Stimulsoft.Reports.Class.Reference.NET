---
title: "StiMargin Class"
---

## StiMargin Class

**Namespace:** `Stimulsoft.Report.Dashboard`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMargin
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMargin()` | Creates a new object of the type StiMargin. |
| `StiMargin(double all)` | Creates a new object of the type StiMargin. |
| `StiMargin(double left, double top, double right, double bottom)` | Creates a new object of the type StiMargin. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Bottom** | double |  |
| **Left** | double |  |
| **Right** | double |  |
| **Top** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool | Tests to see whether the specified object is a StiMargin with the same dimensions as this StiMargin. |
| **GetHashCode** | int | Returns a hash code for this StiMargins structure. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiMargin](StiMargin.md) |  |
| **IsEmpty** | bool |  |

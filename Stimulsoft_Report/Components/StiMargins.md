---
title: "StiMargins Class"
---

## StiMargins Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMargins
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMargins**() | Creates a new object of the type StiMargins. |
| **StiMargins**(double all) | Creates a new object of the type StiMargins. |
| **StiMargins**(double left, double right, double top, double bottom) | Creates a new object of the type StiMargins. |

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
| **Apply** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Equals** | bool | Tests to see whether the specified object is a SizeD with the same dimensions as this SizeD. |
| **GetHashCode** | int | Returns a hash code for this StiMargins structure. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiMargins](StiMargins.md) |  |
| **IsEmpty** | bool |  |

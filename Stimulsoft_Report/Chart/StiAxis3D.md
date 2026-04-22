---
title: "StiAxis3D Class"
---

## StiAxis3D Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiAxis3D
```

### Inheritance

Implements: IStiAxis3D  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxis3D**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Area** | [IStiAxisArea3D](IStiAxisArea3D.md) |  |
| **Core** | StiAxisCoreXF3D |  |
| **Info** | [StiAxisInfoXF3D](StiAxisInfoXF3D.md) |  |
| **Labels** | IStiAxisLabels3D |  |
| **LineColor** | Color |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeVisible** | bool |  |

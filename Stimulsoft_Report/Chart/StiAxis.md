---
title: "StiAxis Class"
---

## StiAxis Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiAxis
```

### Inheritance

Implements: IStiAxis  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiAxis()` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Area** | [IStiAxisArea](IStiAxisArea.md) |  |
| **ArrowStyle** | [StiArrowStyle](StiArrowStyle.md) |  |
| **Core** | StiAxisCoreXF |  |
| **Info** | [StiAxisInfoXF](StiAxisInfoXF.md) |  |
| **Interaction** | IStiAxisInteraction |  |
| **LineColor** | Color |  |
| **LineStyle** | [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md) |  |
| **LineWidth** | float |  |
| **LogarithmicScale** | bool |  |
| **Range** | IStiAxisRange |  |
| **StartFromZero** | bool |  |
| **Ticks** | IStiAxisTicks |  |
| **Visible** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShouldSerializeRange** | bool |  |
| **ShouldSerializeVisible** | bool |  |

---
title: "StiIndicatorVisual Class"
---

## StiIndicatorVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Indicator`  
**Assembly:** `Stimulsoft.Dashboard`

This is a class to work with the indicator element visualization.

```csharp
public class StiIndicatorVisual
```

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIndicatorVisual**(StiIndicatorElement element, List<[StiIndicatorIteration](StiIndicatorIteration.md)> iterations) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Element** | StiIndicatorElement |  |
| **Iterations** | List<[StiIndicatorIteration](StiIndicatorIteration.md)> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws a visual object on specified context and at specified location. |
| **GetElementSide** | float |  |
| **GetTargetValues** | List<decimal?> |  |
| **MeasureFontSize** | void |  |

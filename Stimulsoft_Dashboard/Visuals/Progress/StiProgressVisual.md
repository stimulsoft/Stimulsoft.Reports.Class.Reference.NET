---
title: "StiProgressVisual Class"
---

## StiProgressVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Progress`  
**Assembly:** `Stimulsoft.Dashboard`

This is a base class to work with the progress element visualization.

```csharp
public abstract class StiProgressVisual
```

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiProgressVisual**(StiProgressElement element, List<[StiProgressIteration](StiProgressIteration.md)> iterations) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Element** | StiProgressElement |  |
| **Iterations** | List<[StiProgressIteration](StiProgressIteration.md)> |  |
| **MinElementSide** | byte |  |
| **MinFontSize** | byte |  |
| **Style** | [StiProgressElementStyle](../../../Stimulsoft_Report/Dashboard/Styles/StiProgressElementStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColor** | Color |  |
| **GetColors** | Color[] |  |
| **GetDisplayText** | string |  |
| **GetInteractionDataGeom** | [StiInteractionDataGeom](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiInteractionDataGeom.md) |  |
| **GetTargetValues** | List<decimal> |  |
| **GetTextValues** | List<string> |  |
| **ProcessColor** | Color |  |
| **ProcessFontName** | string |  |
| **ProcessFontStyle** | FontStyle |  |
| **ProcessForeColor** | Color |  |
| **ProcessTrackColor** | Color |  |

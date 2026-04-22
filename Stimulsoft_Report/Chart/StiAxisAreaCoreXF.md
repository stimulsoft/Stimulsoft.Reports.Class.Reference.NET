---
title: "StiAxisAreaCoreXF Class"
---

## StiAxisAreaCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiAxisAreaCoreXF
```

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisAreaCoreXF**(IStiArea area) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BlockScrollValueX** | bool |  |
| **BlockScrollValueY** | bool |  |
| **ScrollDragStartValue** | double |  |
| **ScrollValueX** | double | Gets or sets left position of view area in scrollable area for Axis X. |
| **ScrollValueY** | double | Gets or sets left position of view area in scrollable area for Axis Y. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void | Applying specified style to this area. |
| **CheckShowEdgeValues** | void |  |
| **CheckStripLinesAndMaximumMinimumXAxis** | void | Gets minimum and maximum values if specified YAxis from calculated StripLines collection. |
| **CheckStripLinesAndMaximumMinimumYAxis** | void | Gets minimum and maximum values of specified XAxis from calculated StripLines collection. |
| **CreateStripLinesXAxis** | void | Creates Strip lines collection for XAxis. |
| **CreateStripLinesYAxis** | void | Creates Strip lines collection for YAxis. |
| **GetDividerRightY** | double | Returns position on right y of zero line for y axis. |
| **GetDividerTopX** | double | Returns position on x top of zero line for x axis. |
| **GetDividerX** | double | Returns position on x of zero line for x axis. |
| **GetDividerXD** | double |  |
| **GetDividerY** | double | Returns position on y of zero line for y axis. |
| **GetNextLowerDigit** `static` | double |  |
| **PrepareInfo** | void |  |
| **PrepareRange** | void |  |
| **Render** | StiCellGeom |  |
| **SwitchOff** | void | Internal use only. |

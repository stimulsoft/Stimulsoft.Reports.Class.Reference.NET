---
title: "StiSubReport Class"
---

## StiSubReport Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSubReport
```

### Inheritance

Inherits from: StiContainer  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSubReport()` | Creates a new component of the type StiSubReport. |
| `StiSubReport([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect)` | Creates a new component of the type StiSubReport. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **KeepSubReportTogether** | bool |  |
| **Parameters** | StiParametersCollection |  |
| **SubReportPageGuid** | string |  |
| **SubReportUrl** | string |  |
| **ToolboxCategory** | [StiToolboxCategory](StiToolboxCategory.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanContainIn** | bool | May this container be located in the specified component. |
| **Clone** *(+1 overloads)* | object |  |
| **Convert** | void | Converts a component out of one unit into another. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Returns events collection of this component. |
| **GetExternalSubReport** | [StiReport](../StiReport.md) | Returns the SubReport template for rendering. |
| **GetSubReportForPage** `static` | [StiSubReport](StiSubReport.md) |  |
| **GetSubReportFromFile** | [StiReport](../StiReport.md) | Returns the SubReport from specified path. |
| **GetSubReportFromUrl** | [StiReport](../StiReport.md) | Returns the SubReport from specified url. |
| **InvokeFillParameters** | void | Raises the FillParameters event. |
| **LoadFromJsonObject** | void |  |
| **OnFillParameters** | void | Raises the FillParameters event. |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

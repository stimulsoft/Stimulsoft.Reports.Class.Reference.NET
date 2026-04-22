---
title: "StiPageInfoV2 Class"
---

## StiPageInfoV2 Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPageInfoV2
```

### Inheritance

Inherits from: [StiComponentInfo](../Engine/StiComponentInfo.md)  

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IndexOfStartRenderedPages** | int | The index of the page from which the construction of containers on the page started. |
| **IsReportTitlesRendered** | bool | If true, then ReportTitleBand's have already been built and there is no need to build them for this page. |
| **MasterDataBand** | StiDataBand | Used to specify the MasterComponent when building SubPage's. |
| **PositionFromBottom** | double | Contains the position of the bottom print after static band output. Used to define the bottom print position of CrossTab's output, as well as for outputting cross primitives. |
| **PositionFromTop** | double | Contains the top print position after static band output. Used to define the top print position of CrossTab's output, as well as for outputting cross primitives. |
| **RenderedCount** | int | Number of rendered pages. |

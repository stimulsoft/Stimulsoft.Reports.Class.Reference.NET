---
title: "StiPackedReportSLService Class"
---

## StiPackedReportSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save/load packed reports.

```csharp
public class StiPackedReportSLService
```

### Inheritance

Inherits from: [StiReportSLService](StiReportSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a report from the stream. |
| **LoadAsync** | Task | Loads asynchronously a report from the stream. |
| **Save** | void | Saves report in the stream. |
| **SaveAsync** | Task | Saves asynchronously report in the stream. |

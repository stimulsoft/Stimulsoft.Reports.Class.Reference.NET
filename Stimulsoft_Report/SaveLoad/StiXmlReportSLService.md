---
title: "StiXmlReportSLService Class"
---

## StiXmlReportSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save/load reports.

```csharp
public class StiXmlReportSLService
```

### Inheritance

Inherits from: [StiReportSLService](StiReportSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a report from the stream. |
| **LoadAsync** | Task | Loads a report from the stream. |
| **Save** | void | Saves report in the stream. |
| **SaveAsync** | Task | Saves asynchronously report in the stream. |

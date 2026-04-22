---
title: "StiEngineV1 Class"
---

## StiEngineV1 Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

Summary description for StiEngineV1.

```csharp
public class StiEngineV1
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiEngineV1([StiReport](../StiReport.md) report)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsUsedResetPageNumber** | bool |  |
| **PageInProgress** | StiPage | Internal use only. |
| **RealPageNumber** | int | Gets or sets an index of the current page printed taking into consideration segmented pages. Number starts from 1. |
| **Report** | [StiReport](../StiReport.md) |  |
| **ReportPageNumbers** | Hashtable |  |
| **ReportTotalPageCounts** | Hashtable |  |
| **RequreResetPageNumber** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ProcessResetPageNumber** | void | Internal use only. |
| **ResetPageNumber** | void | Internal use only. |

---
title: "StiProcessExportEventArgs Class"
---

## StiProcessExportEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

Describes an argument for the event ProcessExport.

```csharp
public class StiProcessExportEventArgs
```

### Inheritance

Inherits from: [StiExportEventArgs](StiExportEventArgs.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiProcessExportEventArgs([StiExportFormat](../StiExportFormat.md) format, [StiExportService](../Export/StiExportService.md) exportService, Stream stream, [StiExportSettings](../Export/StiExportSettings.md) settings)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ExportService** | [StiExportService](../Export/StiExportService.md) |  |
| **ExportSettings** | [StiExportSettings](../Export/StiExportSettings.md) |  |
| **Processed** | bool |  |
| **Stream** | Stream |  |

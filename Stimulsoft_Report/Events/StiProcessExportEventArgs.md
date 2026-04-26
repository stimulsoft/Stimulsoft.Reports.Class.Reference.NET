---
title: "StiProcessExportEventArgs Class"
---

## StiProcessExportEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

Describes an argument for the event ProcessExport.

### Inheritance

Inherits from: [StiExportEventArgs](StiExportEventArgs.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiProcessExportEventArgs**([StiExportFormat](../root/StiExportFormat.md) format, [StiExportService](../Export/StiExportService.md) exportService, Stream stream, [StiExportSettings](../Export/StiExportSettings.md) settings) |  |

**StiProcessExportEventArgs**(**format**: [StiExportFormat](../root/StiExportFormat.md), **exportService**: [StiExportService](../Export/StiExportService.md), **stream**: Stream, **settings**: [StiExportSettings](../Export/StiExportSettings.md))

**Parameters**

- **format** ([StiExportFormat](../root/StiExportFormat.md))  
- **exportService** ([StiExportService](../Export/StiExportService.md))  
- **stream** (Stream)  
- **settings** ([StiExportSettings](../Export/StiExportSettings.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ExportService** | [StiExportService](../Export/StiExportService.md) |  |
| **ExportSettings** | [StiExportSettings](../Export/StiExportSettings.md) |  |
| **Processed** | bool |  |
| **Stream** | Stream |  |

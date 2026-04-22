---
title: "StiHtml5ExportService Class"
---

## StiHtml5ExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiHtml5ExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiHtml5ExportService()` | Creates an instance of the class for the HTML export. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the HTML5 file. Also rendered report can be sent via e-mail. |
| **ExportHtml** | void | Exports a document to the HTML5. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for Html files. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **HtmlWriter** | [StiHtmlTextWriter](StiHtmlTextWriter.md) |  |

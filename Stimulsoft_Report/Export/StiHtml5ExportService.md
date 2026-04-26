---
title: "StiHtml5ExportService Class"
---

## StiHtml5ExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHtml5ExportService**() | Creates an instance of the class for the HTML export. |

**StiHtml5ExportService**()

Creates an instance of the class for the HTML export.


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the HTML5 file. Also rendered report can be sent via e-mail. |
| **ExportHtml** | void | Exports a document to the HTML5. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for Html files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the HTML5 file. Also rendered report can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportHtml

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiHtmlExportSettings): void

Exports a document to the HTML5.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **settings** (StiHtmlExportSettings)  


---

#### ExportTo

**ExportTo**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiExportSettings](StiExportSettings.md)): void

Exports a document to the stream without dialog of the saving file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream in which report will be exported.  
- **settings** ([StiExportSettings](StiExportSettings.md)) — A settings for the report exporting.  


---

#### GetFilter

**GetFilter**(): string

Returns a filter for Html files.

**Returns** string — Returns a filter for Html files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **HtmlWriter** | [StiHtmlTextWriter](StiHtmlTextWriter.md) |  |

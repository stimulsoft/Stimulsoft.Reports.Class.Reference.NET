---
title: "StiDataExportService Class"
---

## StiDataExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to a csv file. |
| **ExportData** | void | Exports a rendered report to a csv file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns the filter of all available services which serves for saving, loading a document. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to a csv file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportData

**ExportData**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiDataExportSettings): void

Exports a rendered report to a csv file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **settings** (StiDataExportSettings)  


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

Returns the filter of all available services which serves for saving, loading a document.

**Returns** string — Filter.


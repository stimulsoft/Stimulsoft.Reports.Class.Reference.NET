---
title: "StiXpsExportService Class"
---

## StiXpsExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Xps file. Also exported document can be sent via e-mail. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **ExportXps** *(+3 overloads)* | void | Exports rendered report to an Xps file. |
| **GetFilter** | string | Returns a filter for the Excel files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the Xps file. Also exported document can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportTo

**ExportTo**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiExportSettings](StiExportSettings.md)): void

Exports a document to the stream without dialog of the saving file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream in which report will be exported.  
- **settings** ([StiExportSettings](StiExportSettings.md)) — A settings for the report exporting.  


---

#### ExportXps

**ExportXps**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports rendered report to an Xps file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportXps**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports rendered report to an Excel file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportXps**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports rendered report to an Xps file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportXps**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiXpsExportSettings](StiXpsExportSettings.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** ([StiXpsExportSettings](StiXpsExportSettings.md))  


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the Excel files.

**Returns** string — Returns a filter for the Excel files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bottom** | double |  |
| **Component** | StiComponent |  |
| **Height** | double |  |
| **Right** | double |  |
| **Width** | double |  |
| **X** | double |  |
| **Y** | double |  |

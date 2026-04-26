---
title: "StiDbfExportService Class"
---

## StiDbfExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a document to the file. |
| **ExportDbf** *(+5 overloads)* | void | Exports rendered report to a dbf file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the dbf files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a document to the file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether is exported report will be sended via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportDbf

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **codePage**: [StiDbfCodePages](StiDbfCodePages.md)): void

Exports rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **codePage** ([StiDbfCodePages](StiDbfCodePages.md)) — A parameter which sets a code page of the exported file.  

---

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **pageRange**: [StiPagesRange](../root/StiPagesRange.md), **codePage**: [StiDbfCodePages](StiDbfCodePages.md)): void

Exports rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes pages range of the document for the export.  
- **codePage** ([StiDbfCodePages](StiDbfCodePages.md)) — A parameter which sets a code page of the exported file.  

---

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  

---

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md), **codePage**: [StiDbfCodePages](StiDbfCodePages.md)): void

Exports a rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  
- **codePage** ([StiDbfCodePages](StiDbfCodePages.md)) — A parameter which sets a code page of the exported file.  

---

**ExportDbf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiDataExportSettings): void

Exports a rendered report to a dbf file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
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

Returns a filter for the dbf files.

**Returns** string — String with filter.


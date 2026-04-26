---
title: "StiRtfExportService Class"
---

## StiRtfExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports rendered report to the RTF file. Also file may be sent via e-mail. |
| **ExportRtf** *(+6 overloads)* | void | Exports a rendered report to the RTF file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Rtf files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports rendered report to the RTF file. Also file may be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportRtf

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting of a rendered report.  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **exportMode**: [StiRtfExportMode](StiRtfExportMode.md)): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **exportMode** ([StiRtfExportMode](StiRtfExportMode.md)) — A parameter for setting exporting modes of a document.  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **exportMode**: [StiRtfExportMode](StiRtfExportMode.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **exportMode** ([StiRtfExportMode](StiRtfExportMode.md)) — A parameter for setting exporting modes of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **exportMode**: [StiRtfExportMode](StiRtfExportMode.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md), **usePageHeadersAndFooters**: bool): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **exportMode** ([StiRtfExportMode](StiRtfExportMode.md)) — A parameter for setting exporting modes of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  
- **usePageHeadersAndFooters** (bool)  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **codePage**: int, **exportMode**: [StiRtfExportMode](StiRtfExportMode.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered report to the RTF file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **codePage** (int) — A code page of the exported document.  
- **exportMode** ([StiRtfExportMode](StiRtfExportMode.md)) — A parameter for setting exporting modes of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportRtf**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiRtfExportSettings](StiRtfExportSettings.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** ([StiRtfExportSettings](StiRtfExportSettings.md))  


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

Returns a filter for the Rtf files.

**Returns** string — Returns a filter for the Rtf files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Bold** | bool |  |
| **Component** | StiComponent | A Component. |
| **FontNumber** | int |  |
| **FontSize** | int |  |
| **Height** | int | A Border height. |
| **Italic** | bool |  |
| **Name** | string |  |
| **RightToLeft** | bool |  |
| **TextColor** | int |  |
| **Underline** | bool |  |
| **Width** | int | A Border width. |
| **X** | int | A coordinate of the X frame. |
| **Y** | int | A coordinate of the Y frame. |

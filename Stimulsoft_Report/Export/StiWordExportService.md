---
title: "StiWordExportService Class"
---

## StiWordExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Word file. Also exported document can be sent via e-mail. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **ExportWord** *(+3 overloads)* | void | Exports rendered report to an Word file. |
| **GenerateDocumentProtection** | void |  |
| **GetFilter** | string | Returns a filter for the Word files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the Word file. Also exported document can be sent via e-mail.

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

#### ExportWord

**ExportWord**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports rendered report to an Word file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportWord**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports rendered report to an Word file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportWord**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports rendered report to an Word file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportWord**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiWordExportSettings](StiWordExportSettings.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** ([StiWordExportSettings](StiWordExportSettings.md))  


---

#### GenerateDocumentProtection

**GenerateDocumentProtection**(**writer**: XmlTextWriter, **strPassword**: string): void

**Parameters**

- **writer** (XmlTextWriter)  
- **strPassword** (string)  


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the Word files.

**Returns** string — Returns a filter for the Word files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Bold** | bool |  |
| **FontName** | string |  |
| **FontSize** | int |  |
| **Italic** | bool |  |
| **Name** | string |  |
| **RightToLeft** | bool |  |
| **TextColor** | Color |  |
| **Underline** | bool |  |

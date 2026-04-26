---
title: "StiOdtExportService Class"
---

## StiOdtExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Odt file. Also exported document can be sent via e-mail. |
| **ExportOdt** *(+3 overloads)* | void | Exports rendered report to an Odt file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Odt files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the Odt file. Also exported document can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportOdt

**ExportOdt**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports rendered report to an Odt file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportOdt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports rendered report to an Odt file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportOdt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports rendered report to an Odt file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportOdt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiOdtExportSettings](StiOdtExportSettings.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** ([StiOdtExportSettings](StiOdtExportSettings.md))  


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

Returns a filter for the Odt files.

**Returns** string — Returns a filter for the Odt files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Angle** | int |  |
| **BackColor** | Color |  |
| **Bold** | bool |  |
| **BorderBottom** | string |  |
| **BorderLeft** | string |  |
| **BorderRight** | string |  |
| **BorderTop** | string |  |
| **FontColor** | Color |  |
| **FontName** | string |  |
| **FontSize** | float |  |
| **HorAlign** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Italic** | bool |  |
| **Underline** | bool |  |
| **VertAlign** | [StiVertAlignment](../../Stimulsoft_Base/Drawing/StiVertAlignment.md) |  |

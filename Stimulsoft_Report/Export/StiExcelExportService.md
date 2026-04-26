---
title: "StiExcelExportService Class"
---

## StiExcelExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Excel file. Also exported document can be sent via e-mail. |
| **ExportExcel** *(+4 overloads)* | void | Exports rendered report to an Excel file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Excel files. |
| **WriteDG** | void |  |
| **WriteDGG** | void |  |
| **WriteToStream** | void |  |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the Excel file. Also exported document can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportExcel

**ExportExcel**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports rendered report to an Excel file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportExcel**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports rendered report to an Excel file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportExcel**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports rendered report to an Excel file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportExcel**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md), **useOnePageHeaderAndFooter**: bool): void

Exports rendered report to an Excel file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  
- **useOnePageHeaderAndFooter** (bool) — If true then the first page header and the last page footer will be exported for all exported documents.  

---

**ExportExcel**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiExcelExportSettings): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** (StiExcelExportSettings)  


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

Returns a filter for the Excel files.

**Returns** string — Returns a filter for the Excel files.


---

#### WriteDG

**WriteDG**(**imageList**: ArrayList, **startImageIndex**: int): void

**Parameters**

- **imageList** (ArrayList)  
- **startImageIndex** (int)  


---

#### WriteDGG

**WriteDGG**(**imageList**: ArrayList): void

**Parameters**

- **imageList** (ArrayList)  


---

#### WriteToStream

**WriteToStream**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bold** | bool |  |
| **Bookmark** | string |  |
| **Charset** | int |  |
| **Color** | int |  |
| **ColorIndexBackground** | int |  |
| **ColorIndexBottom** | int |  |
| **ColorIndexLeft** | int |  |
| **ColorIndexPattern** | int |  |
| **ColorIndexRight** | int |  |
| **ColorIndexTop** | int |  |
| **Description** | string |  |
| **FillPatern** | int |  |
| **FirstColumn** | int |  |
| **FirstRow** | int |  |
| **FontIndex** | int |  |
| **FormatIndex** | int |  |
| **Height** | int |  |
| **HorAlign** | int |  |
| **Italic** | bool |  |
| **LastColumn** | int |  |
| **LastRow** | int |  |
| **LineStyleBottom** | int |  |
| **LineStyleLeft** | int |  |
| **LineStyleRight** | int |  |
| **LineStyleTop** | int |  |
| **MemBookmarks** | int[] |  |
| **Name** | string |  |
| **ParentStyleXF** | int |  |
| **Range** | CellRangeAddress |  |
| **Strikeout** | bool |  |
| **TextDirection** | int |  |
| **TextRotationAngle** | int |  |
| **TextWrapped** | int |  |
| **Underlined** | bool |  |
| **UsedAttrib** | int |  |
| **VertAlign** | int |  |
| **XFType** | int |  |
| **mem** | MemoryStream |  |

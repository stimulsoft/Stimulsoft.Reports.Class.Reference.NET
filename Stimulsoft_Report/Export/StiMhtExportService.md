---
title: "StiMhtExportService Class"
---

## StiMhtExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the MHT format. Also file may be sent via e-mail. |
| **ExportMht** *(+5 overloads)* | void | Exports a rendered report to the MHT format. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for Mht files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the MHT format. Also file may be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — If true then the result of the exporting will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportMht

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **zoom**: double, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **zoom** (double) — A zoom of the exported document. Default value is 1.  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Specifies a format of the images in the resulted Mht document.  

---

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **zoom**: double, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **zoom** (double) — A zoom of the exported document. Default value is 1.  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Specifies a format of the images in the resulted Mht document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportMht**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiHtmlExportSettings): void

Exports a rendered report to the MHT format.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
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

Returns a filter for Mht files.

**Returns** string — Returns a filter for Mht files.


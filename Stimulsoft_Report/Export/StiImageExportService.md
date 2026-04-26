---
title: "StiImageExportService Class"
---

## StiImageExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiImageExportService**() |  |

**StiImageExportService**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered document to the file as image. |
| **ExportImage** *(+4 overloads)* | void | Exports a rendered document to the file as image. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for files with bmp images. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered document to the file as image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportImage

**ExportImage**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **imageFormat**: [StiImageFormat](StiImageFormat.md)): void

Exports a rendered document to the file as image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **imageFormat** ([StiImageFormat](StiImageFormat.md)) — Returns format of the image.  

---

**ExportImage**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **imageFormat**: [StiImageFormat](StiImageFormat.md)): void

Exports a rendered document to the stream as image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **imageFormat** ([StiImageFormat](StiImageFormat.md)) — A parameter which sets format of the resulted image.  

---

**ExportImage**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **imageFormat**: [StiImageFormat](StiImageFormat.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered document to the stream as an image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **imageFormat** ([StiImageFormat](StiImageFormat.md)) — A parameter which sets a format of the resulted image.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportImage**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **imageZoom**: double, **cutEdges**: bool, **imageFormat**: [StiImageFormat](StiImageFormat.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered document to the stream as an image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **imageZoom** (double) — A parameter which sets zoom of the resulted image.  
- **cutEdges** (bool) — A parameter which cuts edges of the resulted image after the export.  
- **imageFormat** ([StiImageFormat](StiImageFormat.md)) — A parameter which sets format of the resulted image.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportImage**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiImageExportSettings): void

Exports a rendered document to the stream as an image.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** (StiImageExportSettings)  


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

Returns a filter for files with bmp images.

**Returns** string — Returns a filter for files with bmp images.


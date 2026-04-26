---
title: "StiTxtExportService Class"
---

## StiTxtExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **ExportTxt** *(+3 overloads)* | void | Exports a rendered report to the text file. |
| **GetFilter** | string | Returns a filter for text files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — If true then the result of the exporting will be sent via e-mail.  
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

#### ExportTxt

**ExportTxt**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a rendered report to the text file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportTxt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a rendered report to the stream in text file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for the export.  

---

**ExportTxt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **encoding**: Encoding, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a rendered report to the stream in the text file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for the export.  
- **encoding** (Encoding) — A code page of a text.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — A Range of a page for exporting.  

---

**ExportTxt**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiTxtExportSettings](StiTxtExportSettings.md)): void

Exports a rendered report to the stream in the text file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for exporting.  
- **settings** ([StiTxtExportSettings](StiTxtExportSettings.md)) — Export settings.  


---

#### GetFilter

**GetFilter**(): string

Returns a filter for text files.

**Returns** string — Returns a filter for text files.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bold** | bool |  |
| **Codes** | string |  |
| **Italic** | bool |  |
| **Underline** | bool |  |

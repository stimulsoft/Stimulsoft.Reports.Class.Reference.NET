---
title: "StiExportService Class"
---

## StiExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultExtension** | string | Gets or sets a default extension of export. |
| **ExportFormat** | [StiExportFormat](../root/StiExportFormat.md) |  |
| **ExportNameInMenu** | string | Gets an export name in the context menu. |
| **GroupCategory** | string | Gets a group of the export in the context menu. |
| **MultipleFiles** | bool | Gets a value indicating a number of files in exported document as a result of export of one page of the rendered report. |
| **OwnerWindow** | object |  |
| **Position** | int | Gets a position of the export in the context menu. 0-PDF, 1-HTML, 2-RTF, 3-XML, 4-EXCEL, 5-EXCELXML, 6-TEXT 10-BMP, 11-GIF, 12-JPEG, 13-PNG, 14-TIFF, 20-EMF |
| **Progress** | [IStiProgressInformation](../root/IStiProgressInformation.md) |  |
| **RenderedPagesCount** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseProgress** | void |  |
| **Export** *(+4 overloads)* | void | Exports a document to the stream. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for files of the export format. |
| **GetFilters** `static` | string | Returns the filter of all available services which serves for saving, loading a document. |
| **GetOrderFileName** `static` | string |  |
| **InvokeExporting** *(+2 overloads)* | void |  |
| **OnExporting** | void |  |
| **OpenFile** | void |  |
| **ProcessFile** | void |  |
| **SendEMail** *(+1 overloads)* | void |  |
| **ShowProgress** | void |  |

---

### Method Details

#### CloseProgress

**CloseProgress**(): void


---

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **file**: string): void

Exports a document to the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **file** (string) — A file for the export of a document.  

---

**Export**(**report**: [StiReport](../root/StiReport.md), **file**: string, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a document to the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **file** (string) — A file for the export of a document.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

---

**Export**(**report**: [StiReport](../root/StiReport.md), **file**: string, **sendEMail**: bool): void

Exports a document to the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **file** (string) — A file for the export of a document.  
- **sendEMail** (bool) — A parameter indicating whether is exported report will be sended via e-mail.  

---

**Export**(**report**: [StiReport](../root/StiReport.md), **file**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a document to the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **file** (string) — A file for the export of a document.  
- **sendEMail** (bool) — A parameter indicating whether is exported report will be sended via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

---

**Export**(**report**: [StiReport](../root/StiReport.md)): void

Exports a document to the stream with dialog of saving file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  


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

Returns a filter for files of the export format.

**Returns** string — String with filter.


---

#### GetFilters `static`

**GetFilters**(): string

Returns the filter of all available services which serves for saving, loading a document.

**Returns** string — A Filter.


---

#### GetOrderFileName `static`

**GetOrderFileName**(**baseName**: string, **index**: int, **totalPagesCount**: int, **extension**: string): string

**Parameters**

- **baseName** (string)  
- **index** (int)  
- **totalPagesCount** (int)  
- **extension** (string)  

**Returns** string


---

#### InvokeExporting

**InvokeExporting**(**page**: StiPage, **pages**: [StiPagesCollection](../Components/StiPagesCollection.md), **currentPass**: int, **maximumPass**: int): void

**Parameters**

- **page** (StiPage)  
- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  
- **currentPass** (int)  
- **maximumPass** (int)  

---

**InvokeExporting**(**value**: int, **maximum**: int, **currentPass**: int, **maximumPass**: int): void

**Parameters**

- **value** (int)  
- **maximum** (int)  
- **currentPass** (int)  
- **maximumPass** (int)  

---

**InvokeExporting**(**e**: [StiExportingEventArgs](StiExportingEventArgs.md)): void

**Parameters**

- **e** ([StiExportingEventArgs](StiExportingEventArgs.md))  


---

#### OnExporting

**OnExporting**(**e**: [StiExportingEventArgs](StiExportingEventArgs.md)): void

**Parameters**

- **e** ([StiExportingEventArgs](StiExportingEventArgs.md))  


---

#### OpenFile

**OpenFile**(**fileName**: string): void

**Parameters**

- **fileName** (string)  


---

#### ProcessFile

**ProcessFile**(**sendEMail**: bool, **openAfterExport**: bool, **fileName**: string, **report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **sendEMail** (bool)  
- **openAfterExport** (bool)  
- **fileName** (string)  
- **report** ([StiReport](../root/StiReport.md))  


---

#### SendEMail

**SendEMail**(**subject**: string, **body**: string, **filePath**: string): void

**Parameters**

- **subject** (string)  
- **body** (string)  
- **filePath** (string)  

---

**SendEMail**(**recipient**: string, **subject**: string, **body**: string, **filePath**: string): void

**Parameters**

- **recipient** (string)  
- **subject** (string)  
- **body** (string)  
- **filePath** (string)  


---

#### ShowProgress

**ShowProgress**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Exporting** | StiExportingEventHandler | An event which fires when report is being exported. |

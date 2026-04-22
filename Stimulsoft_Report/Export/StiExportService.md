---
title: "StiExportService Class"
---

## StiExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiExportService
```

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultExtension** | string | Gets or sets a default extension of export. |
| **ExportFormat** | [StiExportFormat](../StiExportFormat.md) |  |
| **ExportNameInMenu** | string | Gets an export name in the context menu. |
| **GroupCategory** | string | Gets a group of the export in the context menu. |
| **MultipleFiles** | bool | Gets a value indicating a number of files in exported document as a result of export of one page of the rendered report. |
| **OwnerWindow** | object |  |
| **Position** | int | Gets a position of the export in the context menu. 0-PDF, 1-HTML, 2-RTF, 3-XML, 4-EXCEL, 5-EXCELXML, 6-TEXT 10-BMP, 11-GIF, 12-JPEG, 13-PNG, 14-TIFF, 20-EMF |
| **Progress** | [IStiProgressInformation](../IStiProgressInformation.md) |  |
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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Exporting** | StiExportingEventHandler | An event which fires when report is being exported. |

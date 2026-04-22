---
title: "StiHtmlExportService Class"
---

## StiHtmlExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiHtmlExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiHtmlExportService()` | Creates an instance of the class for the HTML export. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClearOnFinish** | bool |  |
| **HtmlImageHost** | [StiHtmlImageHost](StiHtmlImageHost.md) | Internal use only. |
| **Nonce** | string |  |
| **RenderAsDocument** | bool | Internal use only. |
| **RenderStyles** | bool |  |
| **RenderWebInteractions** | bool |  |
| **RenderWebViewer** | bool |  |
| **Styles** | ArrayList |  |
| **TotalPageHeight** | double | Internal use only. |
| **TotalPageWidth** | double | Internal use only. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddCoord** | void | Internal use only. |
| **Clear** | void |  |
| **Export** | void | Exports a rendered report to the HTML file. Also rendered report can be sent via e-mail. |
| **ExportHtml** *(+6 overloads)* | void | Exports a document to the HTML. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetChartScript** | string |  |
| **GetFile** `static` *(+1 overloads)* | byte[] | Gets the object placed in assembly. |
| **GetFilter** | string | Returns a filter for Html files. |
| **GetImage** `static` | [Bitmap](../../Stimulsoft_Drawing/Bitmap.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DHeight** | double |  |
| **DWidth** | double |  |
| **FullUrl** | string |  |
| **Height** | string |  |
| **HtmlWriter** | [StiHtmlTextWriter](StiHtmlTextWriter.md) |  |
| **Parent** | int |  |
| **TableRender** | [StiHtmlTableRender](StiHtmlTableRender.md) |  |
| **Title** | string |  |
| **Url** | string |  |
| **Used** | bool |  |
| **Width** | string |  |

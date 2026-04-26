---
title: "StiHtmlExportService Class"
---

## StiHtmlExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHtmlExportService**() | Creates an instance of the class for the HTML export. |

**StiHtmlExportService**()

Creates an instance of the class for the HTML export.


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
| **GetImage** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |

---

### Method Details

#### AddCoord

**AddCoord**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

Internal use only.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — A rectangle.  


---

#### Clear

**Clear**(): void


---

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the HTML file. Also rendered report can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportHtml

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **zoom**: double, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **zoom** (double) — Sets zoom of the exported images.  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Specifies a format of the images in the resulted HTML document.  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **zoom**: double, **imageFormat**: [ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md), **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **zoom** (double) — A zoom of the exported document. Default value is 1.  
- **imageFormat** ([ImageFormat](../../Stimulsoft_Drawing/Imaging/ImageFormat.md)) — Specifies a format of the images in the resulted HTML document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiHtmlExportSettings): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A rendered report which is to be exported.  
- **stream** (Stream) — A stream for the export of a document.  
- **settings** (StiHtmlExportSettings)  

---

**ExportHtml**(**report**: [StiReport](../root/StiReport.md), **writer**: [StiHtmlTextWriter](StiHtmlTextWriter.md), **settings**: StiHtmlExportSettings, **pages**: [StiPagesCollection](../Components/StiPagesCollection.md)): void

Exports a document to the HTML.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **writer** ([StiHtmlTextWriter](StiHtmlTextWriter.md))  
- **settings** (StiHtmlExportSettings)  
- **pages** ([StiPagesCollection](../Components/StiPagesCollection.md))  


---

#### ExportTo

**ExportTo**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiExportSettings](StiExportSettings.md)): void

Exports a document to the stream without dialog of the saving file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream in which report will be exported.  
- **settings** ([StiExportSettings](StiExportSettings.md)) — A settings for the report exporting.  


---

#### GetChartScript

**GetChartScript**(): string

**Returns** string


---

#### GetFile `static`

**GetFile**(**assemblyName**: string, **fileName**: string): byte[]

Gets the object placed in assembly.

**Parameters**

- **assemblyName** (string) — The name of assembly in which the object is placed.  
- **fileName** (string) — The name of the file to look for.  

**Returns** byte[] — The object.

---

**GetFile**(**imageAssembly**: Assembly, **fileName**: string): byte[]

Gets the Image object placed in assembly.

**Parameters**

- **imageAssembly** (Assembly) — Assembly in which is the Image object is placed.  
- **fileName** (string) — The name of the image file to look for.  

**Returns** byte[] — The Image object.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for Html files.

**Returns** string — Returns a filter for Html files.


---

#### GetImage `static`

**GetImage**(**assemblyName**: string, **imageName**: string, **makeTransparent**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **assemblyName** (string)  
- **imageName** (string)  
- **makeTransparent** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


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

---
title: "StiExcel2007ExportService Class"
---

## StiExcel2007ExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MaximumSheetHeight** `static` | int | Gets or sets a value indicating maximum sheet height in rows. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **EqualDataBorder** | bool |  |
| **EqualDataFill** | bool |  |
| **EqualDataFont** | bool |  |
| **EqualDataXF** | bool |  |
| **Export** | void | Exports a rendered report to the Excel file. Also exported document can be sent via e-mail. |
| **ExportExcel** *(+3 overloads)* | void | Exports rendered report to an Excel file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Excel files. |

---

### Method Details

#### EqualDataBorder

**EqualDataBorder**(**db**: DataBorder): bool

**Parameters**

- **db** (DataBorder)  

**Returns** bool


---

#### EqualDataFill

**EqualDataFill**(**df**: DataFill): bool

**Parameters**

- **df** (DataFill)  

**Returns** bool


---

#### EqualDataFont

**EqualDataFont**(**df**: DataFont): bool

**Parameters**

- **df** (DataFont)  

**Returns** bool


---

#### EqualDataXF

**EqualDataXF**(**xf**: DataXF): bool

**Parameters**

- **xf** (DataXF)  

**Returns** bool


---

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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BgColor** | Color |  |
| **Bold** | bool |  |
| **Bookmark** | string |  |
| **BorderBottom** | [StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md) |  |
| **BorderIndex** | int |  |
| **BorderLeft** | [StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md) |  |
| **BorderRight** | [StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md) |  |
| **BorderTop** | [StiBorderSide](../../Stimulsoft_Base/Drawing/StiBorderSide.md) |  |
| **Charset** | int |  |
| **Color** | Color |  |
| **Color** | Color |  |
| **Column** | int |  |
| **Description** | string |  |
| **Editable** | bool |  |
| **Family** | int |  |
| **FgColor** | Color |  |
| **FillIndex** | int |  |
| **FirstColumn** | int |  |
| **FirstRow** | int |  |
| **FontIndex** | int |  |
| **FormatIndex** | int |  |
| **Height** | double |  |
| **HorAlign** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Italic** | bool |  |
| **LastColumn** | int |  |
| **LastRow** | int |  |
| **Name** | string |  |
| **Position** | [PointD](../../Stimulsoft_Base/Drawing/PointD.md) |  |
| **Range** | CellRangeAddress |  |
| **RightToLeft** | bool |  |
| **Row** | int |  |
| **Size** | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **Strikeout** | bool |  |
| **TextRotationAngle** | int |  |
| **TextWrapped** | bool |  |
| **Type** | string |  |
| **Underlined** | bool |  |
| **VertAlign** | [StiVertAlignment](../../Stimulsoft_Base/Drawing/StiVertAlignment.md) |  |
| **XFId** | int |  |

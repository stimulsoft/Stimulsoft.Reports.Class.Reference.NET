---
title: "StiExcel2007ExportService Class"
---

## StiExcel2007ExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiExcel2007ExportService
```

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

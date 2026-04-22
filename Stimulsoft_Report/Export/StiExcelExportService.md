---
title: "StiExcelExportService Class"
---

## StiExcelExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiExcelExportService
```

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

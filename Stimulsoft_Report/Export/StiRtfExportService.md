---
title: "StiRtfExportService Class"
---

## StiRtfExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiRtfExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports rendered report to the RTF file. Also file may be sent via e-mail. |
| **ExportRtf** *(+6 overloads)* | void | Exports a rendered report to the RTF file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Rtf files. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Bold** | bool |  |
| **Component** | StiComponent | A Component. |
| **FontNumber** | int |  |
| **FontSize** | int |  |
| **Height** | int | A Border height. |
| **Italic** | bool |  |
| **Name** | string |  |
| **RightToLeft** | bool |  |
| **TextColor** | int |  |
| **Underline** | bool |  |
| **Width** | int | A Border width. |
| **X** | int | A coordinate of the X frame. |
| **Y** | int | A coordinate of the Y frame. |

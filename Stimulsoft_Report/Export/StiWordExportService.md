---
title: "StiWordExportService Class"
---

## StiWordExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiWordExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Word file. Also exported document can be sent via e-mail. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **ExportWord** *(+3 overloads)* | void | Exports rendered report to an Word file. |
| **GenerateDocumentProtection** | void |  |
| **GetFilter** | string | Returns a filter for the Word files. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Alignment** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Bold** | bool |  |
| **FontName** | string |  |
| **FontSize** | int |  |
| **Italic** | bool |  |
| **Name** | string |  |
| **RightToLeft** | bool |  |
| **TextColor** | Color |  |
| **Underline** | bool |  |

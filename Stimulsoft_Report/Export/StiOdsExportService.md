---
title: "StiOdsExportService Class"
---

## StiOdsExportService Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiOdsExportService
```

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Ods file. Also exported document can be sent via e-mail. |
| **ExportOds** *(+3 overloads)* | void | Exports rendered report to an Ods file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Ods files. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Angle** | int |  |
| **BackColor** | Color |  |
| **Bold** | bool |  |
| **BorderBottom** | string |  |
| **BorderLeft** | string |  |
| **BorderRight** | string |  |
| **BorderTop** | string |  |
| **CurrencyNegativePattern** | string |  |
| **CurrencyPositionBefore** | bool |  |
| **CurrencyPositivePattern** | string |  |
| **CurrencySymbol** | string |  |
| **DataStyle** | int |  |
| **DateTimeFormatString** | string |  |
| **DecimalComma** | char |  |
| **DecimalDigits** | int |  |
| **FontColor** | Color |  |
| **FontName** | string |  |
| **FontSize** | float |  |
| **GroupDigits** | int |  |
| **GroupSeparator** | string |  |
| **HorAlign** | [StiTextHorAlignment](../../Stimulsoft_Base/Drawing/StiTextHorAlignment.md) |  |
| **Italic** | bool |  |
| **NegativeBraces** | bool |  |
| **Underline** | bool |  |
| **VertAlign** | [StiVertAlignment](../../Stimulsoft_Base/Drawing/StiVertAlignment.md) |  |
| **Wordwrap** | bool |  |
| **isCurrency** | bool |  |
| **isDate** | bool |  |
| **isDefaultFormat** | bool |  |
| **isNumeric** | bool |  |
| **isPercent** | bool |  |
| **isTime** | bool |  |

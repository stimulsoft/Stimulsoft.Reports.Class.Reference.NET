---
title: "StiOdsExportService Class"
---

## StiOdsExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the Ods file. Also exported document can be sent via e-mail. |
| **ExportOds** *(+3 overloads)* | void | Exports rendered report to an Ods file. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **GetFilter** | string | Returns a filter for the Ods files. |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the Ods file. Also exported document can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportOds

**ExportOds**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports rendered report to an Ods file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportOds**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports rendered report to an Ods file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportOds**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **pageRange**: [StiPagesRange](../root/StiPagesRange.md)): void

Exports rendered report to an Ods file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **pageRange** ([StiPagesRange](../root/StiPagesRange.md)) — Describes range of pages of the document for the export.  

---

**ExportOds**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiOdsExportSettings](StiOdsExportSettings.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **stream** (Stream)  
- **settings** ([StiOdsExportSettings](StiOdsExportSettings.md))  


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

Returns a filter for the Ods files.

**Returns** string — Returns a filter for the Ods files.


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

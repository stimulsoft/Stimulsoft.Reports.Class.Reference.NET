---
title: "StiXmlExportService Class"
---

## StiXmlExportService Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [StiExportService](StiExportService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Export** | void | Exports a rendered report to the XML file. Also the file can be sent via e-mail. |
| **ExportTo** | void | Exports a document to the stream without dialog of the saving file. |
| **ExportXml** *(+2 overloads)* | void | Exports a rendered report to the XML file. |
| **GetFilter** | string | Returns a filter for xml files. |
| **WriteDataSetToStream** | void |  |

---

### Method Details

#### Export

**Export**(**report**: [StiReport](../root/StiReport.md), **fileName**: string, **sendEMail**: bool, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): void

Exports a rendered report to the XML file. Also the file can be sent via e-mail.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  
- **sendEMail** (bool) — A parameter indicating whether the exported report will be sent via e-mail.  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  


---

#### ExportTo

**ExportTo**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: [StiExportSettings](StiExportSettings.md)): void

Exports a document to the stream without dialog of the saving file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream in which report will be exported.  
- **settings** ([StiExportSettings](StiExportSettings.md)) — A settings for the report exporting.  


---

#### ExportXml

**ExportXml**(**report**: [StiReport](../root/StiReport.md), **fileName**: string): void

Exports a rendered report to the XML file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **fileName** (string) — A name of the file for exporting a rendered report.  

---

**ExportXml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Exports a rendered report to the XML file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  

---

**ExportXml**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream, **settings**: StiDataExportSettings): void

Exports a rendered report to the XML file.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — A report which is to be exported.  
- **stream** (Stream) — A stream for export of a document.  
- **settings** (StiDataExportSettings) — A export settings.  


---

#### GetFilter

**GetFilter**(): string

Returns a filter for xml files.

**Returns** string — Returns a filter for xml files.


---

#### WriteDataSetToStream

**WriteDataSetToStream**(**dataSet**: DataSet, **stream**: Stream, **settings**: StiDataExportSettings): void

**Parameters**

- **dataSet** (DataSet)  
- **stream** (Stream)  
- **settings** (StiDataExportSettings)  


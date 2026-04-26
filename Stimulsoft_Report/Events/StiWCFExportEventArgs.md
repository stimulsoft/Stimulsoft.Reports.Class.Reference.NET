---
title: "StiWCFExportEventArgs Class"
---

## StiWCFExportEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWCFExportEventArgs**(bytedata , string filter, [StiReport](../root/StiReport.md) report) |  |

**StiWCFExportEventArgs**(****: bytedata, **filter**: string, **report**: [StiReport](../root/StiReport.md))

**Parameters**

- **** (bytedata)  
- **filter** (string)  
- **report** ([StiReport](../root/StiReport.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Data** | byte[] |  |
| **Designer** | [IStiDesignerBase](../Design/IStiDesignerBase.md) |  |
| **Filter** | string |  |
| **Handled** | bool |  |
| **Viewer** | [IStiViewerControl](../Viewer/IStiViewerControl.md) |  |

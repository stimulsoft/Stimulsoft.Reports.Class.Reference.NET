---
title: "StiWCFEventArgs Class"
---

## StiWCFEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWCFEventArgs**(bytedata , [IStiViewerControl](../Viewer/IStiViewerControl.md) viewer) |  |
| **StiWCFEventArgs**(bytedata , [IStiDesignerBase](../Design/IStiDesignerBase.md) designer) |  |

**StiWCFEventArgs**(****: bytedata, **viewer**: [IStiViewerControl](../Viewer/IStiViewerControl.md))

**Parameters**

- **** (bytedata)  
- **viewer** ([IStiViewerControl](../Viewer/IStiViewerControl.md))  

---

**StiWCFEventArgs**(****: bytedata, **designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md))

**Parameters**

- **** (bytedata)  
- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Data** | byte[] |  |
| **Designer** | [IStiDesignerBase](../Design/IStiDesignerBase.md) |  |
| **Handled** | bool |  |
| **Viewer** | [IStiViewerControl](../Viewer/IStiViewerControl.md) |  |

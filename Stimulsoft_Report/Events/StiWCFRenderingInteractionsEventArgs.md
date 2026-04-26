---
title: "StiWCFRenderingInteractionsEventArgs Class"
---

## StiWCFRenderingInteractionsEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiWCFRenderingInteractionsEventArgs**(bytedata , [StiInteractionType](../root/StiInteractionType.md) interactionType, [IStiViewerControl](../Viewer/IStiViewerControl.md) viewer) |  |

**StiWCFRenderingInteractionsEventArgs**(****: bytedata, **interactionType**: [StiInteractionType](../root/StiInteractionType.md), **viewer**: [IStiViewerControl](../Viewer/IStiViewerControl.md))

**Parameters**

- **** (bytedata)  
- **interactionType** ([StiInteractionType](../root/StiInteractionType.md))  
- **viewer** ([IStiViewerControl](../Viewer/IStiViewerControl.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Data** | byte[] |  |
| **DrillDownMode** | [StiDrillDownMode](../Components/StiDrillDownMode.md) |  |
| **Handled** | bool |  |
| **InteractionType** | [StiInteractionType](../root/StiInteractionType.md) |  |
| **Page** | StiPage |  |
| **Viewer** | [IStiViewerControl](../Viewer/IStiViewerControl.md) |  |

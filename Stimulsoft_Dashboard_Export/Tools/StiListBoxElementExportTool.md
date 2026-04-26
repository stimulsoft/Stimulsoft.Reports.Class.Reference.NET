---
title: "StiListBoxElementExportTool Class"
---

## StiListBoxElementExportTool Class

**Namespace:** `Stimulsoft.Dashboard.Export.Tools`

### Inheritance

Inherits from: [StiElementExportTool](StiElementExportTool.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Render** | void |  |
| **RenderItems** *(+1 overloads)* | void |  |

---

### Method Details

#### Render

**Render**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): void

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  


---

#### RenderItems

**RenderItems**(**destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **allowOpacity**: bool, **scaleFactor**: double): void

**Parameters**

- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **allowOpacity** (bool)  
- **scaleFactor** (double)  

---

**RenderItems**(**destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **values**: IList<string>, **checks**: IList<[StiCheckStyle](../../Stimulsoft_Report/Components/StiCheckStyle.md)>, ****: IList<bool>expanders, **allowOpacity**: bool, **scaleFactor**: double): void

**Parameters**

- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **values** (IList<string>)  
- **checks** (IList<[StiCheckStyle](../../Stimulsoft_Report/Components/StiCheckStyle.md)>)  
- **** (IList<bool>expanders)  
- **allowOpacity** (bool)  
- **scaleFactor** (double)  


---
title: "StiElementExportTool Class"
---

## StiElementExportTool Class

**Namespace:** `Stimulsoft.Dashboard.Export.Tools`

### Inheritance

Inherits from: [StiExportTool](StiExportTool.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **Format** | string |  |
| **GetDataTable** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **PaintAtom** | void |  |
| **PaintContent** | void |  |
| **Render** | void |  |
| **RenderContent** | void |  |
| **RenderEmptyDataMessage** | bool |  |

---

### Method Details

#### Draw

**Draw**(**element**: IStiElement, **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **scale**: double, **allowOpacity**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **element** (IStiElement)  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **scale** (double)  
- **allowOpacity** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### Format

**Format**(**element**: IStiControlElement, **value**: object): string

**Parameters**

- **element** (IStiControlElement)  
- **value** (object)  

**Returns** string


---

#### GetDataTable `static`

**GetDataTable**(**element**: IStiElement): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **element** (IStiElement)  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### PaintAtom

**PaintAtom**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintContent

**PaintContent**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### Render

**Render**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): void

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  


---

#### RenderContent

**RenderContent**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): void

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  


---

#### RenderEmptyDataMessage

**RenderEmptyDataMessage**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): bool

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  

**Returns** bool


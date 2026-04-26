---
title: "StiExportTool Class"
---

## StiExportTool Class

**Namespace:** `Stimulsoft.Dashboard.Export.Tools`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetScaleFactor** `static` | double |  |
| **GetTool** `static` | [StiExportTool](StiExportTool.md) |  |
| **IsAllowOpacity** `static` | bool |  |
| **Render** | void |  |

---

### Method Details

#### GetScaleFactor `static`

**GetScaleFactor**(**destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **settings**: StiDashboardExportSettings): double

**Parameters**

- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **settings** (StiDashboardExportSettings)  

**Returns** double


---

#### GetTool `static`

**GetTool**(**type**: Type): [StiExportTool](StiExportTool.md)

**Parameters**

- **type** (Type)  

**Returns** [StiExportTool](StiExportTool.md)


---

#### IsAllowOpacity `static`

**IsAllowOpacity**(**settings**: StiDashboardExportSettings): bool

**Parameters**

- **settings** (StiDashboardExportSettings)  

**Returns** bool


---

#### Render

**Render**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): void

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  


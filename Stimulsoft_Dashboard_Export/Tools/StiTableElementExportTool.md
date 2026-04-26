---
title: "StiTableElementExportTool Class"
---

## StiTableElementExportTool Class

**Namespace:** `Stimulsoft.Dashboard.Export.Tools`

### Inheritance

Inherits from: [StiElementExportTool](StiElementExportTool.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ProcessDataTableWithTopN** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Render** | void |  |
| **RenderCellsForViewer** `static` | List<List<Hashtable>> |  |

---

### Method Details

#### ProcessDataTableWithTopN `static`

**ProcessDataTableWithTopN**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### Render

**Render**(**element**: IStiElement, **destination**: [StiPanel](../../Stimulsoft_Report/Components/StiPanel.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **settings**: StiDashboardExportSettings): void

**Parameters**

- **element** (IStiElement)  
- **destination** ([StiPanel](../../Stimulsoft_Report/Components/StiPanel.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **settings** (StiDashboardExportSettings)  


---

#### RenderCellsForViewer `static`

**RenderCellsForViewer**(**element**: IStiTableElement, **tableWidth**: double, **tableElementGridPageNumbers**: Hashtable, **onlyCurrentPageData**: bool): List<List<Hashtable>>

**Parameters**

- **element** (IStiTableElement)  
- **tableWidth** (double)  
- **tableElementGridPageNumbers** (Hashtable)  
- **onlyCurrentPageData** (bool)  

**Returns** List<List<Hashtable>>


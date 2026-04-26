---
title: "StiChartAtom Class"
---

## StiChartAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiChartAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |
| **StiChartAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation) |  |

**StiChartAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

---

**StiChartAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **animation**: [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **animation** ([StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Chart** | [StiChart](../../Stimulsoft_Report/Chart/StiChart.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Paint** | void |  |
| **Render** | void |  |

---

### Method Details

#### Paint

**Paint**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### Render

**Render**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ChartElement** | StiChartElement |  |

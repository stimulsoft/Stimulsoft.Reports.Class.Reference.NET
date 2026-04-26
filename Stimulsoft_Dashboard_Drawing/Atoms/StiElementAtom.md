---
title: "StiElementAtom Class"
---

## StiElementAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiElementAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |
| **StiElementAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation) |  |

**StiElementAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

---

**StiElementAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **animation**: [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **animation** ([StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataTable** | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Element** | IStiElement |  |
| **Location** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Get** `static` | [StiElementAtom](StiElementAtom.md) |  |
| **Paint** | void |  |
| **PaintElement** `static` | void |  |
| **Render** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### Get `static`

**Get**(**location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **animationEngine**: [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md), **isExporting**: bool): [StiElementAtom](StiElementAtom.md)

**Parameters**

- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **animationEngine** ([StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))  
- **isExporting** (bool)  

**Returns** [StiElementAtom](StiElementAtom.md)


---

#### Paint

**Paint**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintElement `static`

**PaintElement**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **isExporting**: bool): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **isExporting** (bool)  


---

#### Render

**Render**(): void


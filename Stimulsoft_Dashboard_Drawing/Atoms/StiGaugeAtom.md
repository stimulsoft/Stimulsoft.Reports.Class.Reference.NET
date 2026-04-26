---
title: "StiGaugeAtom Class"
---

## StiGaugeAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGaugeAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |
| **StiGaugeAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation) |  |

**StiGaugeAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

---

**StiGaugeAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **animation**: [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **animation** ([StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetContentRectangle** | RectangleF |  |
| **Paint** | void |  |
| **PaintTitle** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **Render** | void |  |

---

### Method Details

#### GetContentRectangle

**GetContentRectangle**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): RectangleF

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  

**Returns** RectangleF


---

#### Paint

**Paint**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintTitle

**PaintTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **titleText**: string, **size**: double): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **titleText** (string)  
- **size** (double)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### Render

**Render**(): void


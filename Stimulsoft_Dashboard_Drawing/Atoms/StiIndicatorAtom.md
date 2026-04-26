---
title: "StiIndicatorAtom Class"
---

## StiIndicatorAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIndicatorAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |

**StiIndicatorAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetContentRectangle** | RectangleF |  |
| **Paint** | void |  |
| **Render** | void |  |

---

### Method Details

#### GetContentRectangle

**GetContentRectangle**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): RectangleF

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** RectangleF


---

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
| **IndicatorElement** | StiIndicatorElement |  |

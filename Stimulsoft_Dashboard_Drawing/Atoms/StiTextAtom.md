---
title: "StiTextAtom Class"
---

## StiTextAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTextAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |

**StiTextAtom**(**element**: IStiElement, **location**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (IStiElement)  
- **location** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetHyperlinkUnderMouse** | string |  |
| **Paint** | void |  |
| **Render** | void |  |

---

### Method Details

#### GetHyperlinkUnderMouse

**GetHyperlinkUnderMouse**(**mousePosition**: Point): string

**Parameters**

- **mousePosition** (Point)  

**Returns** string


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
| **TextElement** | StiTextElement |  |

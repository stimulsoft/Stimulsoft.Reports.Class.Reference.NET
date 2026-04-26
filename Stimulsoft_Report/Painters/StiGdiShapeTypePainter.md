---
title: "StiGdiShapeTypePainter Class"
---

## StiGdiShapeTypePainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiShapeTypePainter](StiShapeTypePainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawShape** `static` *(+1 overloads)* | void |  |
| **GetRect** | RectangleF |  |
| **GetRectLeftRight** | RectangleF |  |
| **GetRectTopBottom** | RectangleF |  |

---

### Method Details

#### DrawShape `static`

**DrawShape**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **shape**: StiShape, ****: Pointpoints, **rect**: RectangleF): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **shape** (StiShape)  
- **** (Pointpoints)  
- **rect** (RectangleF)  

---

**DrawShape**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **shape**: StiShape, **path**: [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md), **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **shape** (StiShape)  
- **path** ([GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md))  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### GetRect

**GetRect**(**shape**: StiShape, **rect**: RectangleF, **zoom**: float): RectangleF

**Parameters**

- **shape** (StiShape)  
- **rect** (RectangleF)  
- **zoom** (float)  

**Returns** RectangleF


---

#### GetRectLeftRight

**GetRectLeftRight**(**shape**: StiShape, **rect**: RectangleF, **zoom**: float): RectangleF

**Parameters**

- **shape** (StiShape)  
- **rect** (RectangleF)  
- **zoom** (float)  

**Returns** RectangleF


---

#### GetRectTopBottom

**GetRectTopBottom**(**shape**: StiShape, **rect**: RectangleF, **zoom**: float): RectangleF

**Parameters**

- **shape** (StiShape)  
- **rect** (RectangleF)  
- **zoom** (float)  

**Returns** RectangleF


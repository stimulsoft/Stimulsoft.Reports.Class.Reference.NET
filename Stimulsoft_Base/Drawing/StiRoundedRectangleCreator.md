---
title: "StiRoundedRectangleCreator Class"
---

## StiRoundedRectangleCreator Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** `static` *(+1 overloads)* | [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md) |  |
| **DrawRoundedRect** `static` | void |  |

---

### Method Details

#### Create `static`

**Create**(**rect**: RectangleF, **radius**: float, **scale**: float): [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)

**Parameters**

- **rect** (RectangleF)  
- **radius** (float)  
- **scale** (float)  

**Returns** [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)

---

**Create**(**rect**: RectangleF, **radius**: StiCornerRadius, **scale**: float): [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)

**Parameters**

- **rect** (RectangleF)  
- **radius** (StiCornerRadius)  
- **scale** (float)  

**Returns** [GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)


---

#### DrawRoundedRect `static`

**DrawRoundedRect**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **pen**: [Pen](../../Stimulsoft_Drawing/root/Pen.md), **rect**: RectangleF, **radius**: StiCornerRadius, **sides**: [StiBorderSides](StiBorderSides.md), **scale**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **pen** ([Pen](../../Stimulsoft_Drawing/root/Pen.md))  
- **rect** (RectangleF)  
- **radius** (StiCornerRadius)  
- **sides** ([StiBorderSides](StiBorderSides.md))  
- **scale** (float)  


---
title: "StiStandardTextRenderer Class"
---

## StiStandardTextRenderer Class

**Namespace:** `Stimulsoft.Report.Components`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawString** `static` *(+1 overloads)* | void |  |
| **DrawStringGdi** `static` | void |  |
| **MeasureString** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |

---

### Method Details

#### DrawString `static`

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string, **textBox**: StiText): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **text** (string)  
- **textBox** (StiText)  

---

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string, **textBox**: StiText, **zoom**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **text** (string)  
- **textBox** (StiText)  
- **zoom** (float)  


---

#### DrawStringGdi `static`

**DrawStringGdi**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string, **textBox**: StiText, **zoom**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **text** (string)  
- **textBox** (StiText)  
- **zoom** (float)  


---

#### MeasureString `static`

**MeasureString**(**maxWidth**: double, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **textBox**: StiText): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **maxWidth** (double)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **textBox** (StiText)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


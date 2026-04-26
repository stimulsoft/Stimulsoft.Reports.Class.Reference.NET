---
title: "StiContextSvgHelper Class"
---

## StiContextSvgHelper Class

**Namespace:** `Stimulsoft.Report.Export.Services.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CorrectRectLabel** `static` | RectangleF |  |
| **WriteFillBrush** `static` | string |  |
| **WriteFillBrushMouserOver** `static` | void |  |
| **WriteGeoms** `static` | void |  |
| **WriteTooltip** `static` | void |  |

---

### Method Details

#### CorrectRectLabel `static`

**CorrectRectLabel**(**rotationMode**: [StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md), **textRect**: RectangleF): RectangleF

**Parameters**

- **rotationMode** ([StiRotationMode](../../../../Stimulsoft_Base/Drawing/StiRotationMode.md))  
- **textRect** (RectangleF)  

**Returns** RectangleF


---

#### WriteFillBrush `static`

**WriteFillBrush**(**writer**: XmlTextWriter, **brush**: object, **rect**: RectangleF, **dx**: float, **dy**: float): string

**Parameters**

- **writer** (XmlTextWriter)  
- **brush** (object)  
- **rect** (RectangleF)  
- **dx** (float)  
- **dy** (float)  

**Returns** string


---

#### WriteFillBrushMouserOver `static`

**WriteFillBrushMouserOver**(**writer**: XmlTextWriter, **brushOver**: object, **rect**: RectangleF, **dx**: float, **dy**: float): void

**Parameters**

- **writer** (XmlTextWriter)  
- **brushOver** (object)  
- **rect** (RectangleF)  
- **dx** (float)  
- **dy** (float)  


---

#### WriteGeoms `static`

**WriteGeoms**(**writer**: XmlTextWriter, **context**: [StiContext](../../../Stimulsoft/Base/Context/StiContext.md), **needAnimation**: bool): void

**Parameters**

- **writer** (XmlTextWriter)  
- **context** ([StiContext](../../../Stimulsoft/Base/Context/StiContext.md))  
- **needAnimation** (bool)  


---

#### WriteTooltip `static`

**WriteTooltip**(**writer**: XmlTextWriter, **tooltip**: string): void

**Parameters**

- **writer** (XmlTextWriter)  
- **tooltip** (string)  


---
title: "StiGaugeSvgHelper Class"
---

## StiGaugeSvgHelper Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetArcPath** `static` | string |  |
| **WriteFillBrush** `static` | string |  |
| **WriteGauge** `static` *(+1 overloads)* | void |  |
| **WriteText** `static` | void |  |

---

### Method Details

#### GetArcPath `static`

**GetArcPath**(**rect**: RectangleF, **path_**: string, **startAngle**: float, **sweepAngle**: double, **isSetStartPoint**: bool): string

**Parameters**

- **rect** (RectangleF)  
- **path_** (string)  
- **startAngle** (float)  
- **sweepAngle** (double)  
- **isSetStartPoint** (bool)  

**Returns** string


---

#### WriteFillBrush `static`

**WriteFillBrush**(**writer**: XmlTextWriter, **brush**: object, **rect**: RectangleF): string

**Parameters**

- **writer** (XmlTextWriter)  
- **brush** (object)  
- **rect** (RectangleF)  

**Returns** string


---

#### WriteGauge `static`

**WriteGauge**(**writer**: XmlTextWriter, **svgData**: [StiSvgData](StiSvgData.md), **zoom**: float, **needAnimation**: bool, **isStyleSample**: bool, **interaction**: [StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md), **brushOver**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)): void

**Parameters**

- **writer** (XmlTextWriter)  
- **svgData** ([StiSvgData](StiSvgData.md))  
- **zoom** (float)  
- **needAnimation** (bool)  
- **isStyleSample** (bool)  
- **interaction** ([StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md))  
- **brushOver** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  

---

**WriteGauge**(**writer**: XmlTextWriter, **svgData**: [StiSvgData](StiSvgData.md), **needAnimation**: bool, **isStyleSample**: bool, **interaction**: [StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md), **brushOver**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)): void

**Parameters**

- **writer** (XmlTextWriter)  
- **svgData** ([StiSvgData](StiSvgData.md))  
- **needAnimation** (bool)  
- **isStyleSample** (bool)  
- **interaction** ([StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md))  
- **brushOver** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  


---

#### WriteText `static`

**WriteText**(**writer**: XmlTextWriter, **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **foreground**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **pointF**: PointF, **size**: float): void

**Parameters**

- **writer** (XmlTextWriter)  
- **text** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **foreground** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **pointF** (PointF)  
- **size** (float)  


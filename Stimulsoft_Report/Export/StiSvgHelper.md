---
title: "StiSvgHelper Class"
---

## StiSvgHelper Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetLineStyleDash** `static` | string |  |
| **GetStyleString** `static` | string |  |
| **RenderCheckBox** `static` | string |  |
| **RenderIcon** `static` | string |  |
| **RenderShape** `static` | MemoryStream |  |
| **RenderShapeAsBase64** `static` | string |  |
| **SaveComponentToString** `static` *(+1 overloads)* | string |  |
| **SaveToStream** `static` | void |  |
| **ToUnits** `static` | string |  |
| **WriteCheckBox** `static` | void |  |

---

### Method Details

#### GetLineStyleDash `static`

**GetLineStyleDash**(**penStyle**: [StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md), **width**: double): string

**Parameters**

- **penStyle** ([StiPenStyle](../../Stimulsoft_Base/Drawing/StiPenStyle.md))  
- **width** (double)  

**Returns** string


---

#### GetStyleString `static`

**GetStyleString**(**font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **textColor**: Color, **useTextDecoration**: bool): string

**Parameters**

- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **textColor** (Color)  
- **useTextDecoration** (bool)  

**Returns** string


---

#### RenderCheckBox `static`

**RenderCheckBox**(**style**: [StiCheckStyle](../Components/StiCheckStyle.md), **contourColor**: Color, **contourSize**: double, **textBrush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **width**: double): string

**Parameters**

- **style** ([StiCheckStyle](../Components/StiCheckStyle.md))  
- **contourColor** (Color)  
- **contourSize** (double)  
- **textBrush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **width** (double)  

**Returns** string


---

#### RenderIcon `static`

**RenderIcon**(**image**: StiImage, **zoom**: float, **baseWidth**: double, **baseHeight**: double): string

**Parameters**

- **image** (StiImage)  
- **zoom** (float)  
- **baseWidth** (double)  
- **baseHeight** (double)  

**Returns** string


---

#### RenderShape `static`

**RenderShape**(**component**: StiComponent): MemoryStream

**Parameters**

- **component** (StiComponent)  

**Returns** MemoryStream


---

#### RenderShapeAsBase64 `static`

**RenderShapeAsBase64**(**component**: StiComponent): string

**Parameters**

- **component** (StiComponent)  

**Returns** string


---

#### SaveComponentToString `static`

**SaveComponentToString**(**component**: StiComponent): string

**Parameters**

- **component** (StiComponent)  

**Returns** string

---

**SaveComponentToString**(**component**: StiComponent, **zoom**: double): string

**Parameters**

- **component** (StiComponent)  
- **zoom** (double)  

**Returns** string


---

#### SaveToStream `static`

**SaveToStream**(**report**: [StiReport](../root/StiReport.md), **page**: StiPage, **stream**: Stream, **compressed**: bool): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **page** (StiPage)  
- **stream** (Stream)  
- **compressed** (bool)  


---

#### ToUnits `static`

**ToUnits**(**number**: double, **digitsLimit**: int): string

**Parameters**

- **number** (double)  
- **digitsLimit** (int)  

**Returns** string


---

#### WriteCheckBox `static`

**WriteCheckBox**(**writer**: XmlTextWriter, **svgData**: [StiSvgData](StiSvgData.md)): void

**Parameters**

- **writer** (XmlTextWriter)  
- **svgData** ([StiSvgData](StiSvgData.md))  


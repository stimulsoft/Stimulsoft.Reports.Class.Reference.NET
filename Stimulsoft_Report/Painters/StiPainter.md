---
title: "StiPainter Class"
---

## StiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetIndicatorPainter** `static` | [StiIndicatorTypePainter](StiIndicatorTypePainter.md) |  |
| **GetPainter** `static` | [StiPainter](StiPainter.md) |  |
| **GetShapePainter** `static` | [StiShapeTypePainter](StiShapeTypePainter.md) |  |
| **GetThumbnail** | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Gets a thumbnail image of the component. |
| **Paint** | void |  |
| **PaintHighlight** | void |  |
| **PaintSelection** | void |  |

---

### Method Details

#### GetImage

**GetImage**(**component**: StiComponent, **zoom**: float, **format**: [StiExportFormat](../root/StiExportFormat.md)): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **component** (StiComponent)  
- **zoom** (float)  
- **format** ([StiExportFormat](../root/StiExportFormat.md))  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetIndicatorPainter `static`

**GetIndicatorPainter**(**type**: Type, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [StiIndicatorTypePainter](StiIndicatorTypePainter.md)

**Parameters**

- **type** (Type)  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [StiIndicatorTypePainter](StiIndicatorTypePainter.md)


---

#### GetPainter `static`

**GetPainter**(**type**: Type, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [StiPainter](StiPainter.md)

**Parameters**

- **type** (Type)  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [StiPainter](StiPainter.md)


---

#### GetShapePainter `static`

**GetShapePainter**(**type**: Type, **guiMode**: [StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md)): [StiShapeTypePainter](StiShapeTypePainter.md)

**Parameters**

- **type** (Type)  
- **guiMode** ([StiGuiMode](../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [StiShapeTypePainter](StiShapeTypePainter.md)


---

#### GetThumbnail

**GetThumbnail**(**component**: StiComponent, **width**: int, **height**: int, **isDesignTime**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Gets a thumbnail image of the component.

**Parameters**

- **component** (StiComponent)  
- **width** (int) — Width of the thumbnail image.  
- **height** (int) — Height of the thumbnail image.  
- **isDesignTime** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — A thumbnail image of the specified size.


---

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintHighlight

**PaintHighlight**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintSelection

**PaintSelection**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


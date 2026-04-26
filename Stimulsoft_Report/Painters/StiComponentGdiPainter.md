---
title: "StiComponentGdiPainter Class"
---

## StiComponentGdiPainter Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Inherits from: [StiGdiPainter](StiGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetSelectionCornerColor** | Color |  |
| **GetThumbnail** | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Gets a thumbnail image of the component. |
| **Paint** | void |  |
| **PaintBorder** *(+3 overloads)* | void |  |
| **PaintConditions** | void | Paints conditions and filters of a component. |
| **PaintConditionsAndFilter** | void | Paints conditions and filters of a component. |
| **PaintEvents** | void | Paints events of a component. |
| **PaintHighlight** | void | Paints the highlight of the specified component. |
| **PaintInheritedImage** | void |  |
| **PaintInteraction** | void |  |
| **PaintMarkers** | void | Paints a markers specified by a Rectangle structure. |
| **PaintNoDefinedStatus** | void |  |
| **PaintOrderAndQuickInfo** | void | Paints order numbers and quick info of a component. |
| **PaintProgress** `static` | void | Paints progress of a component. |
| **PaintQuickButtons** | void | Paints the QuickButtons. |
| **PaintSelection** | void | Paints the selection. |

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

#### GetSelectionCornerColor

**GetSelectionCornerColor**(**comp**: StiComponent): Color

**Parameters**

- **comp** (StiComponent)  

**Returns** Color


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

#### PaintBorder

**PaintBorder**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

---

**PaintBorder**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **drawBorderFormatting**: bool, **drawBorderSides**: bool): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **drawBorderFormatting** (bool)  
- **drawBorderSides** (bool)  

---

**PaintBorder**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **zoom**: double, **drawBorderFormatting**: bool, **drawBorderSides**: bool): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **zoom** (double)  
- **drawBorderFormatting** (bool)  
- **drawBorderSides** (bool)  

---

**PaintBorder**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **zoom**: float, **drawBorderFormatting**: bool, **drawBorderSides**: bool): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **zoom** (float)  
- **drawBorderFormatting** (bool)  
- **drawBorderSides** (bool)  


---

#### PaintConditions

**PaintConditions**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

Paints conditions and filters of a component.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle.  


---

#### PaintConditionsAndFilter

**PaintConditionsAndFilter**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

Paints conditions and filters of a component.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle.  


---

#### PaintEvents

**PaintEvents**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): void

Paints events of a component.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle.  


---

#### PaintHighlight

**PaintHighlight**(**component**: StiComponent, **e**: StiPaintEventArgs): void

Paints the highlight of the specified component.

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintInheritedImage

**PaintInheritedImage**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintInteraction

**PaintInteraction**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### PaintMarkers

**PaintMarkers**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **color**: Color?): void

Paints a markers specified by a Rectangle structure.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to draw on.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — RectangleD structure that represents the rectangle to draw markers.  
- **color** (Color?)  


---

#### PaintNoDefinedStatus

**PaintNoDefinedStatus**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **comp**: StiComponent, **imagePath**: string, **defaultText**: string): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **comp** (StiComponent)  
- **imagePath** (string)  
- **defaultText** (string)  


---

#### PaintOrderAndQuickInfo

**PaintOrderAndQuickInfo**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **number**: string): void

Paints order numbers and quick info of a component.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  
- **number** (string) — A number of the component order for painting.  


---

#### PaintProgress `static`

**PaintProgress**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **progressStatus**: [StiProgressStatus](../../Stimulsoft_Base/Helpers/StiProgressStatus.md), **value**: float?): void

Paints progress of a component.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle.  
- **progressStatus** ([StiProgressStatus](../../Stimulsoft_Base/Helpers/StiProgressStatus.md))  
- **value** (float?)  


---

#### PaintQuickButtons

**PaintQuickButtons**(**component**: StiComponent, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md)): void

Paints the QuickButtons.

**Parameters**

- **component** (StiComponent)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — The Graphics to paint on.  


---

#### PaintSelection

**PaintSelection**(**component**: StiComponent, **e**: StiPaintEventArgs): void

Paints the selection.

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


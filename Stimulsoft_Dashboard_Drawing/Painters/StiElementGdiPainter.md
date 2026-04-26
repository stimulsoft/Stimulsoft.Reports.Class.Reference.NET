---
title: "StiElementGdiPainter Class"
---

## StiElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: [StiComponentGdiPainter](../../Stimulsoft_Report/Painters/StiComponentGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyCornerRadiusAndSetClip** `static` | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **GetElementIdent** | string |  |
| **GetPaintTitleRect** `static` | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **GetSelectionCornerColor** | Color |  |
| **GetTitleText** | string |  |
| **IsDefaultBorder** | bool |  |
| **IsDefined** | bool |  |
| **IsEmptyData** | bool |  |
| **IsNoResult** | bool |  |
| **Paint** | void |  |
| **PaintBackground** | void |  |
| **PaintBorder** | void |  |
| **PaintCheckBoxTitle** | void |  |
| **PaintContent** | void |  |
| **PaintDefaultBorder** | void |  |
| **PaintElementMarkers** | void |  |
| **PaintEmptyData** | void |  |
| **PaintError** | void |  |
| **PaintHighlight** | void |  |
| **PaintNoResult** | void |  |
| **PaintNotDefined** | void |  |
| **PaintNotDefinedStatus** | void |  |
| **PaintNotEnabled** | void |  |
| **PaintRectangleBorder** `static` | void |  |
| **PaintShadow** | void |  |
| **PaintStatus** | void |  |
| **PaintTitle** *(+1 overloads)* | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |

---

### Method Details

#### ApplyCornerRadiusAndSetClip `static`

**ApplyCornerRadiusAndSetClip**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### GetElementIdent

**GetElementIdent**(**element**: object): string

**Parameters**

- **element** (object)  

**Returns** string


---

#### GetPaintTitleRect `static`

**GetPaintTitleRect**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: [IStiTitleElement](../../Stimulsoft_Report/Dashboard/IStiTitleElement.md), **titleText**: string): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** ([IStiTitleElement](../../Stimulsoft_Report/Dashboard/IStiTitleElement.md))  
- **titleText** (string)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### GetSelectionCornerColor

**GetSelectionCornerColor**(**comp**: StiComponent): Color

**Parameters**

- **comp** (StiComponent)  

**Returns** Color


---

#### GetTitleText

**GetTitleText**(**element**: IStiElement): string

**Parameters**

- **element** (IStiElement)  

**Returns** string


---

#### IsDefaultBorder

**IsDefaultBorder**(**element**: IStiElement): bool

**Parameters**

- **element** (IStiElement)  

**Returns** bool


---

#### IsDefined

**IsDefined**(**component**: StiComponent): bool

**Parameters**

- **component** (StiComponent)  

**Returns** bool


---

#### IsEmptyData

**IsEmptyData**(**element**: IStiElement, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): bool

**Parameters**

- **element** (IStiElement)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** bool


---

#### IsNoResult

**IsNoResult**(**element**: IStiElement, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): bool

**Parameters**

- **element** (IStiElement)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** bool


---

#### Paint

**Paint**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintBackground

**PaintBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintBorder

**PaintBorder**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintCheckBoxTitle

**PaintCheckBoxTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintContent

**PaintContent**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintDefaultBorder

**PaintDefaultBorder**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintElementMarkers

**PaintElementMarkers**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintEmptyData

**PaintEmptyData**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **zoom** (double?)  


---

#### PaintError

**PaintError**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  


---

#### PaintHighlight

**PaintHighlight**(**component**: StiComponent, **e**: StiPaintEventArgs): void

**Parameters**

- **component** (StiComponent)  
- **e** (StiPaintEventArgs)  


---

#### PaintNoResult

**PaintNoResult**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  
- **zoom** (double?)  


---

#### PaintNotDefined

**PaintNotDefined**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **zoom** (double?)  


---

#### PaintNotDefinedStatus

**PaintNotDefinedStatus**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **text**: string, **imageName**: string, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **text** (string)  
- **imageName** (string)  
- **zoom** (double?)  


---

#### PaintNotEnabled

**PaintNotEnabled**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **zoom** (double?)  


---

#### PaintRectangleBorder `static`

**PaintRectangleBorder**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **zoom**: float): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **zoom** (float)  


---

#### PaintShadow

**PaintShadow**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintStatus

**PaintStatus**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **element**: IStiElement, **text**: string, **fullImageName**: string, **zoom**: double?): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **element** (IStiElement)  
- **text** (string)  
- **fullImageName** (string)  
- **zoom** (double?)  


---

#### PaintTitle

**PaintTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

---

**PaintTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: [IStiTitleElement](../../Stimulsoft_Report/Dashboard/IStiTitleElement.md), **titleText**: string, **zoom**: double, **isViewer**: bool): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** ([IStiTitleElement](../../Stimulsoft_Report/Dashboard/IStiTitleElement.md))  
- **titleText** (string)  
- **zoom** (double)  
- **isViewer** (bool)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---
title: "StiInteractiveHtmlToolTip Class"
---

## StiInteractiveHtmlToolTip Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls`

### Inheritance

Inherits from: Control  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiInteractiveHtmlToolTip**() |  |

**StiInteractiveHtmlToolTip**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Border** | [StiSimpleBorder](../../Stimulsoft_Base/Drawing/StiSimpleBorder.md) |  |
| **Brush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **Font** | [Font](../../Stimulsoft_Drawing/root/Font.md) |  |
| **HorAlignment** | [StiHorAlignment](../../Stimulsoft_Base/Drawing/StiHorAlignment.md) |  |
| **TextBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **VertAlignment** | [StiVertAlignment](../../Stimulsoft_Base/Drawing/StiVertAlignment.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetBorderContentRect** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **GetHyperlinkUnderMouse** | string |  |
| **Hide** | void |  |
| **OnClick** | void |  |
| **OnLocationChanged** | void |  |
| **OnMouseEnter** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **OnPaintBackground** | void |  |
| **OnVisibleChanged** | void |  |
| **SetHtmlToolTip** | void |  |
| **ShowToolTip** | void |  |

---

### Method Details

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### GetBorderContentRect

**GetBorderContentRect**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **scale**: double): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **scale** (double)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### GetHyperlinkUnderMouse

**GetHyperlinkUnderMouse**(**mousePosition**: Point): string

**Parameters**

- **mousePosition** (Point)  

**Returns** string


---

#### Hide

**Hide**(**control**: Control): void

**Parameters**

- **control** (Control)  


---

#### OnClick

**OnClick**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnLocationChanged

**OnLocationChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseEnter

**OnMouseEnter**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseLeave

**OnMouseLeave**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseMove

**OnMouseMove**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnPaint

**OnPaint**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


---

#### OnPaintBackground

**OnPaintBackground**(**pevent**: PaintEventArgs): void

**Parameters**

- **pevent** (PaintEventArgs)  


---

#### OnVisibleChanged

**OnVisibleChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### SetHtmlToolTip

**SetHtmlToolTip**(**control**: Control, **text**: string): void

**Parameters**

- **control** (Control)  
- **text** (string)  


---

#### ShowToolTip

**ShowToolTip**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Active** | bool |  |
| **referenceRectangle** | Rectangle |  |

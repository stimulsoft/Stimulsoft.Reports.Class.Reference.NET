---
title: "StiActionCheckBox Class"
---

## StiActionCheckBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls`

### Inheritance

Inherits from: CheckBox  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiActionCheckBox**([StiControlColorCollection](StiControlColorCollection.md) colors, Point? position) |  |

**StiActionCheckBox**(**colors**: [StiControlColorCollection](StiControlColorCollection.md), **position**: Point?)

**Parameters**

- **colors** ([StiControlColorCollection](StiControlColorCollection.md))  
- **position** (Point?)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsPressed** | bool |  |
| **SymbolSize** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **OnMouseDown** | void |  |
| **OnMouseUp** | void |  |
| **OnPaint** | void |  |
| **OnPaintBackground** | void |  |
| **PaintBackground** | void |  |
| **PaintImage** | void |  |
| **PaintSymbolIcon** | void |  |
| **PaintText** | void |  |
| **RefreshImageOrIcon** | void |  |

---

### Method Details

#### OnMouseDown

**OnMouseDown**(**mevent**: MouseEventArgs): void

**Parameters**

- **mevent** (MouseEventArgs)  


---

#### OnMouseUp

**OnMouseUp**(**mevent**: MouseEventArgs): void

**Parameters**

- **mevent** (MouseEventArgs)  


---

#### OnPaint

**OnPaint**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


---

#### OnPaintBackground

**OnPaintBackground**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


---

#### PaintBackground

**PaintBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (Rectangle)  


---

#### PaintImage

**PaintImage**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (Rectangle)  


---

#### PaintSymbolIcon

**PaintSymbolIcon**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **imageRect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **imageRect** (Rectangle)  


---

#### PaintText

**PaintText**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (Rectangle)  


---

#### RefreshImageOrIcon

**RefreshImageOrIcon**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IsMouseOver** | bool |  |

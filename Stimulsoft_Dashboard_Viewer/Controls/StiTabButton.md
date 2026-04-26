---
title: "StiTabButton Class"
---

## StiTabButton Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls`

### Inheritance

Inherits from: [StiActionCheckBox](StiActionCheckBox.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTabButton**([StiControlColorCollection](StiControlColorCollection.md) colors, Point position) |  |

**StiTabButton**(**colors**: [StiControlColorCollection](StiControlColorCollection.md), **position**: Point)

**Parameters**

- **colors** ([StiControlColorCollection](StiControlColorCollection.md))  
- **position** (Point)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ShowCloseButton** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalculateAutoWidth** | void |  |
| **OnClick** | void |  |
| **OnMouseEnter** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **PaintBackground** | void |  |

---

### Method Details

#### CalculateAutoWidth

**CalculateAutoWidth**(): void


---

#### OnClick

**OnClick**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseEnter

**OnMouseEnter**(**eventargs**: EventArgs): void

**Parameters**

- **eventargs** (EventArgs)  


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

#### PaintBackground

**PaintBackground**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: Rectangle): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (Rectangle)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **CloseButtonClick** | EventHandler |  |

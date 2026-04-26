---
title: "StiIndicatorControl Class"
---

## StiIndicatorControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.Indicator`

### Inheritance

Inherits from: StiAtomElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIndicatorControl**(IStiElement element) |  |

**StiIndicatorControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HyperlinkString** | string |  |
| **ToolTipString** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **OnClick** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **PaintAtom** | void |  |
| **RecalculateSize** | void |  |
| **RefreshChild** | void |  |

---

### Method Details

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### OnClick

**OnClick**(**e**: EventArgs): void

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

#### PaintAtom

**PaintAtom**(**g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### RecalculateSize

**RecalculateSize**(**rect**: Rectangle): void

**Parameters**

- **rect** (Rectangle)  


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IndicatorAtom** | [StiIndicatorAtom](../../../Stimulsoft_Dashboard_Drawing/Atoms/StiIndicatorAtom.md) |  |
| **IndicatorElement** | IStiIndicatorElement |  |

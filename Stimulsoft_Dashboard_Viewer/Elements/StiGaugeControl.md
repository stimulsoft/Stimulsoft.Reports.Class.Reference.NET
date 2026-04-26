---
title: "StiGaugeControl Class"
---

## StiGaugeControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements`

### Inheritance

Inherits from: StiAtomElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGaugeControl**(IStiElement element) |  |

**StiGaugeControl**(**element**: IStiElement)

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
| **CreateChild** | void |  |
| **Dispose** | void |  |
| **OnClick** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **RecalculateSize** | void |  |
| **RefreshChild** | void |  |

---

### Method Details

#### CreateChild

**CreateChild**(): void


---

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

#### RecalculateSize

**RecalculateSize**(**rect**: Rectangle): void

**Parameters**

- **rect** (Rectangle)  


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **GaugeAtom** | [StiGaugeAtom](../../Stimulsoft_Dashboard_Drawing/Atoms/StiGaugeAtom.md) |  |
| **GaugeElement** | IStiGaugeElement |  |

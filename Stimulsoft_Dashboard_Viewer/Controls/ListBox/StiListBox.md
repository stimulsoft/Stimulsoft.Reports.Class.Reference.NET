---
title: "StiListBox Class"
---

## StiListBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.ListBox`

### Inheritance

Inherits from: System.Windows.Forms.ListBox  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiListBox**() |  |

**StiListBox**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsTransparent** | bool |  |
| **NegativeInRed** | bool |  |
| **ShowRadioButtons** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IndexFromPointV2** | int |  |
| **OnDrawItem** | void |  |
| **OnMeasureItem** | void |  |
| **OnMouseHover** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **OnSelectedIndexChanged** | void |  |

---

### Method Details

#### IndexFromPointV2

**IndexFromPointV2**(**pos**: Point): int

**Parameters**

- **pos** (Point)  

**Returns** int


---

#### OnDrawItem

**OnDrawItem**(**e**: DrawItemEventArgs): void

**Parameters**

- **e** (DrawItemEventArgs)  


---

#### OnMeasureItem

**OnMeasureItem**(**e**: MeasureItemEventArgs): void

**Parameters**

- **e** (MeasureItemEventArgs)  


---

#### OnMouseHover

**OnMouseHover**(**e**: EventArgs): void

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

#### OnSelectedIndexChanged

**OnSelectedIndexChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **TrackingIndexChanged** | StiListBoxTrackingIndexChangedEventHandler |  |

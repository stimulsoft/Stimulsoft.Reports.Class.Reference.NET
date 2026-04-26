---
title: "StiCheckedListBox Class"
---

## StiCheckedListBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.ListBox`

### Inheritance

Inherits from: CheckedListBox  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCheckedListBox**() |  |

**StiCheckedListBox**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BlockSelectedIndexChanged** | bool |  |
| **IsTransparent** | bool |  |
| **NegativeInRed** | bool |  |
| **ShowCheckBoxes** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IndexFromPointV2** | int |  |
| **OnDrawItem** | void |  |
| **OnItemCheck** | void |  |
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

#### OnItemCheck

**OnItemCheck**(**ice**: ItemCheckEventArgs): void

**Parameters**

- **ice** (ItemCheckEventArgs)  


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

---
title: "StiHorizontalListBox Class"
---

## StiHorizontalListBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.ListBox`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHorizontalListBox**() |  |

**StiHorizontalListBox**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsTransparent** | bool |  |
| **Items** | List<[StiListBoxItem](../../../Stimulsoft_Dashboard/Components/ListBox/StiListBoxItem.md)> |  |
| **MultiSelection** | bool |  |
| **NegativeInRed** | bool |  |
| **ScrollBar** | HScrollBar |  |
| **ShowRadioButtons** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **OnMouseDown** | void |  |
| **OnMouseHover** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **OnSizeChanged** | void |  |
| **RefreshUI** | void |  |
| **ResetAllItemsSelection** | void |  |
| **ResetAllItemsSelectionAndSelectFirstOnly** | void |  |
| **SelectAllItems** | void |  |
| **SelectFirstItemOnly** | void |  |

---

### Method Details

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### OnMouseDown

**OnMouseDown**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


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

#### OnSizeChanged

**OnSizeChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### RefreshUI

**RefreshUI**(): void


---

#### ResetAllItemsSelection

**ResetAllItemsSelection**(): void


---

#### ResetAllItemsSelectionAndSelectFirstOnly

**ResetAllItemsSelectionAndSelectFirstOnly**(): void


---

#### SelectAllItems

**SelectAllItems**(): void


---

#### SelectFirstItemOnly

**SelectFirstItemOnly**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ItemSelectionChanged** | StiListBoxItemSelectionChangedEventHandler |  |
| **TrackingIndexChanged** | StiListBoxTrackingIndexChangedEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SelectedIndex** | int |  |
| **SelectedItem** | [StiListBoxItem](../../../Stimulsoft_Dashboard/Components/ListBox/StiListBoxItem.md) |  |
| **SelectedValue** | object |  |

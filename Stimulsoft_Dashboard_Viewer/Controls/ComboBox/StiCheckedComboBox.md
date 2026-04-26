---
title: "StiCheckedComboBox Class"
---

## StiCheckedComboBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.ComboBox`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCheckedComboBox**(StiComboBoxElement element) |  |

**StiCheckedComboBox**(**element**: StiComboBoxElement)

**Parameters**

- **element** (StiComboBoxElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BlockSelectedIndexChanged** | bool |  |
| **IsTransparent** | bool |  |
| **ShowAllValue** | bool |  |
| **ShowSearchBox** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseDropDown** | void |  |
| **Dispose** | void |  |
| **DrawButton** | void |  |
| **GetButtonWidth** | int |  |
| **GetCheckedItems** | List<Components.ComboBox.StiComboBoxItem> |  |
| **OnMouseEnter** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnPaint** | void |  |
| **SetAllItemsCheckState** | void |  |
| **SetAllItemsState** | void |  |
| **SetItemChecked** | void |  |
| **SetItems** | void |  |
| **ShowDropDown** | void |  |

---

### Method Details

#### CloseDropDown

**CloseDropDown**(): void


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### DrawButton

**DrawButton**(**g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### GetButtonWidth

**GetButtonWidth**(): int

**Returns** int


---

#### GetCheckedItems

**GetCheckedItems**(): List<Components.ComboBox.StiComboBoxItem>

**Returns** List<Components.ComboBox.StiComboBoxItem>


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

#### OnMouseUp

**OnMouseUp**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnPaint

**OnPaint**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


---

#### SetAllItemsCheckState

**SetAllItemsCheckState**(**state**: CheckState): void

**Parameters**

- **state** (CheckState)  


---

#### SetAllItemsState

**SetAllItemsState**(**state**: CheckState): void

**Parameters**

- **state** (CheckState)  


---

#### SetItemChecked

**SetItemChecked**(**index**: int, **value**: bool): void

**Parameters**

- **index** (int)  
- **value** (bool)  


---

#### SetItems

**SetItems**(**items**: List<Components.ComboBox.StiComboBoxItem>): void

**Parameters**

- **items** (List<Components.ComboBox.StiComboBoxItem>)  


---

#### ShowDropDown

**ShowDropDown**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DroppedDown** | bool |  |

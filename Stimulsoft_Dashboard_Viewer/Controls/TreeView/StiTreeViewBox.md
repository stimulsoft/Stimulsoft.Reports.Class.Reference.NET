---
title: "StiTreeViewBox Class"
---

## StiTreeViewBox Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.TreeView`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreeViewBox**(StiTreeViewBoxElement element) |  |

**StiTreeViewBox**(**element**: StiTreeViewBoxElement)

**Parameters**

- **element** (StiTreeViewBoxElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCloseDropDownOnDoubleClick** | bool |  |
| **AllowShowCheckedZones** | bool |  |
| **DropDownBackColor** | Color? |  |
| **IsTransparent** | bool |  |
| **NegativeInRed** | bool |  |
| **TextFormat** | StiFormatService |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BeginUpdate** | void |  |
| **CloseDropDown** | void |  |
| **Dispose** | void |  |
| **EndUpdate** | void |  |
| **GetButtonWidth** | int |  |
| **OnMouseEnter** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnPaint** | void |  |
| **ShowDropDown** | void |  |

---

### Method Details

#### BeginUpdate

**BeginUpdate**(): void


---

#### CloseDropDown

**CloseDropDown**(): void


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### EndUpdate

**EndUpdate**(): void


---

#### GetButtonWidth

**GetButtonWidth**(): int

**Returns** int


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

#### ShowDropDown

**ShowDropDown**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DroppedDown** | bool |  |
| **Nodes** | TreeNodeCollection |  |

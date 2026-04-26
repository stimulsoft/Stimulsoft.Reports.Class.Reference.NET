---
title: "StiPivotTableContainerControl Class"
---

## StiPivotTableContainerControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.PivotTable`

### Inheritance

Inherits from: StiBaseElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPivotTableContainerControl**(Control grid, StiPivotTableElement element) |  |

**StiPivotTableContainerControl**(**grid**: Control, **element**: StiPivotTableElement)

**Parameters**

- **grid** (Control)  
- **element** (StiPivotTableElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Container_AfterSizeUpdate** | void |  |
| **Dispose** | void |  |
| **ExpandCollapse** | void |  |
| **GetPanel** | [StiScrollableControl](../StiScrollableControl.md) |  |
| **MakeGrid** | void |  |
| **MouseClickInternal** | void |  |
| **OnMouseClick** | void |  |
| **OnMouseDown** | void |  |
| **OnMouseLeave** *(+1 overloads)* | void |  |
| **OnMouseMove** | void |  |
| **OnPaint** | void |  |
| **ProcessCmdKey** | bool |  |
| **RestoreState** | void |  |
| **SaveState** | void |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### Container_AfterSizeUpdate

**Container_AfterSizeUpdate**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### ExpandCollapse

**ExpandCollapse**(**expand**: bool): void

**Parameters**

- **expand** (bool)  


---

#### GetPanel

**GetPanel**(**control**: Control): [StiScrollableControl](../StiScrollableControl.md)

**Parameters**

- **control** (Control)  

**Returns** [StiScrollableControl](../StiScrollableControl.md)


---

#### MakeGrid

**MakeGrid**(**cross**: [StiCross](../../../Stimulsoft_Report/CrossTab/Core/StiCross.md), **pivot**: StiPivotTableElement): void

**Parameters**

- **cross** ([StiCross](../../../Stimulsoft_Report/CrossTab/Core/StiCross.md))  
- **pivot** (StiPivotTableElement)  


---

#### MouseClickInternal

**MouseClickInternal**(**cx**: int, **cy**: int): void

**Parameters**

- **cx** (int)  
- **cy** (int)  


---

#### OnMouseClick

**OnMouseClick**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnMouseDown

**OnMouseDown**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnMouseLeave

**OnMouseLeave**(): void

---

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

#### ProcessCmdKey

**ProcessCmdKey**(**msg**: Message, **keyData**: Keys): bool

**Parameters**

- **msg** (Message)  
- **keyData** (Keys)  

**Returns** bool


---

#### RestoreState

**RestoreState**(): void


---

#### SaveState

**SaveState**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **pivotTableContainer** | [StiPivotTableContainer](../../../Stimulsoft_Dashboard_Drawing/Painters/PivotTable/StiPivotTableContainer.md) |  |

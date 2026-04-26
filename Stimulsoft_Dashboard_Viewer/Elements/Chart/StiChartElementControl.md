---
title: "StiChartElementControl Class"
---

## StiChartElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.Chart`

### Inheritance

Inherits from: StiAtomElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiChartElementControl**(IStiElement element) |  |

**StiChartElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **OnClick** | void |  |
| **OnMouseDown** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnMouseWheel** | void |  |
| **OnPaint** | void |  |
| **RefreshChild** | void |  |
| **RemoveFilter** | void |  |
| **ResetGeomSelection** | void |  |
| **SwitchFilterMultiOption** | void |  |

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

#### OnMouseDown

**OnMouseDown**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


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

#### OnMouseWheel

**OnMouseWheel**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnPaint

**OnPaint**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


---

#### RemoveFilter

**RemoveFilter**(): void


---

#### ResetGeomSelection

**ResetGeomSelection**(): void


---

#### SwitchFilterMultiOption

**SwitchFilterMultiOption**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ChartAtom** | [StiChartAtom](../../../Stimulsoft_Dashboard_Drawing/Atoms/StiChartAtom.md) |  |
| **Interaction** | StiChartDashboardInteraction |  |

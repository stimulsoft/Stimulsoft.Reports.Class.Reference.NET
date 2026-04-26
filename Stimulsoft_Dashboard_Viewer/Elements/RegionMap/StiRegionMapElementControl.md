---
title: "StiRegionMapElementControl Class"
---

## StiRegionMapElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.RegionMap`

### Inheritance

Inherits from: StiAtomElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRegionMapElementControl**(IStiElement element) |  |

**StiRegionMapElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetInteractiveCheckedState** | List<string> |  |
| **OnClick** | void |  |
| **OnMouseDown** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnMouseWheel** | void |  |
| **OnPaint** | void |  |
| **OnSizeChanged** | void |  |
| **PaintAtom** | void |  |
| **RefreshChild** | void |  |
| **RefreshStatus** | void |  |
| **RemoveFilter** | void |  |
| **SwitchFilterMultiOption** | void |  |

---

### Method Details

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### GetInteractiveCheckedState

**GetInteractiveCheckedState**(): List<string>

**Returns** List<string>


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

#### OnSizeChanged

**OnSizeChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### PaintAtom

**PaintAtom**(**g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md)): void

**Parameters**

- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


---

#### RefreshStatus

**RefreshStatus**(**checkProgressStatus**: bool): void

**Parameters**

- **checkProgressStatus** (bool)  


---

#### RemoveFilter

**RemoveFilter**(): void


---

#### SwitchFilterMultiOption

**SwitchFilterMultiOption**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Interaction** | StiDashboardInteraction |  |
| **RegionMapAtom** | [StiRegionMapAtom](../../../Stimulsoft_Dashboard_Drawing/Atoms/StiRegionMapAtom.md) |  |
| **RegionMapElement** | StiRegionMapElement |  |

---
title: "StiHorizontalListBoxElementControl Class"
---

## StiHorizontalListBoxElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.ListBox`

### Inheritance

Inherits from: [StiListBoxElementControl](StiListBoxElementControl.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHorizontalListBoxElementControl**(IStiElement element) |  |

**StiHorizontalListBoxElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LockRefreshItems** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateChild** | void |  |
| **Dispose** | void |  |
| **DisposeChild** | void |  |
| **GetSelectAllItem** | object |  |
| **ListViewControl_ItemSelectionChanged** | void |  |
| **RefreshControl** | void |  |
| **ResetFilter** | void |  |
| **UpdateTrackingProps** | void |  |

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

#### DisposeChild

**DisposeChild**(): void


---

#### GetSelectAllItem

**GetSelectAllItem**(): object

**Returns** object


---

#### ListViewControl_ItemSelectionChanged

**ListViewControl_ItemSelectionChanged**(**sender**: object, **e**: [StiListBoxItemSelectionChangedEventArgs](../../Controls/ListBox/StiListBoxItemSelectionChangedEventArgs.md)): void

**Parameters**

- **sender** (object)  
- **e** ([StiListBoxItemSelectionChangedEventArgs](../../Controls/ListBox/StiListBoxItemSelectionChangedEventArgs.md))  


---

#### RefreshControl

**RefreshControl**(**sender**: object, **e**: [StiReportControlUpdateEventArgs](../../../Stimulsoft_Report/Events/StiReportControlUpdateEventArgs.md)): void

**Parameters**

- **sender** (object)  
- **e** ([StiReportControlUpdateEventArgs](../../../Stimulsoft_Report/Events/StiReportControlUpdateEventArgs.md))  


---

#### ResetFilter

**ResetFilter**(): void


---

#### UpdateTrackingProps

**UpdateTrackingProps**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ListBoxControl** | [StiHorizontalListBox](../../Controls/ListBox/StiHorizontalListBox.md) |  |

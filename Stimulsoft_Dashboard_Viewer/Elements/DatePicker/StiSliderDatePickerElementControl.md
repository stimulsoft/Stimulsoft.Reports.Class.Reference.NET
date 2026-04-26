---
title: "StiSliderDatePickerElementControl Class"
---

## StiSliderDatePickerElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.DatePicker`

### Inheritance

Inherits from: StiFilterElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSliderDatePickerElementControl**(IStiElement element) |  |

**StiSliderDatePickerElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateChild** | void |  |
| **DisposeChild** | void |  |
| **RefreshChild** | void |  |
| **RefreshControl** | void |  |
| **RefreshFilter** | void |  |
| **RefreshStatus** | void |  |
| **ResetFilter** | void |  |
| **SetDefaultSelection** | void |  |

---

### Method Details

#### CreateChild

**CreateChild**(): void


---

#### DisposeChild

**DisposeChild**(): void


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


---

#### RefreshControl

**RefreshControl**(**sender**: object, **e**: [StiReportControlUpdateEventArgs](../../../Stimulsoft_Report/Events/StiReportControlUpdateEventArgs.md)): void

**Parameters**

- **sender** (object)  
- **e** ([StiReportControlUpdateEventArgs](../../../Stimulsoft_Report/Events/StiReportControlUpdateEventArgs.md))  


---

#### RefreshFilter

**RefreshFilter**(): void


---

#### RefreshStatus

**RefreshStatus**(**checkProgressStatus**: bool): void

**Parameters**

- **checkProgressStatus** (bool)  


---

#### ResetFilter

**ResetFilter**(): void


---

#### SetDefaultSelection

**SetDefaultSelection**(**lockRefresh**: bool): void

**Parameters**

- **lockRefresh** (bool)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DatePickerElement** | StiDatePickerElement |  |

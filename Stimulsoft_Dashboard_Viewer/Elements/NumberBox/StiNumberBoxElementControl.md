---
title: "StiNumberBoxElementControl Class"
---

## StiNumberBoxElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.NumberBox`

### Inheritance

Inherits from: StiFilterElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNumberBoxElementControl**(IStiElement element) |  |

**StiNumberBoxElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateChild** | void |  |
| **Dispose** | void |  |
| **DisposeChild** | void |  |
| **OnSizeChanged** | void |  |
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

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### DisposeChild

**DisposeChild**(): void


---

#### OnSizeChanged

**OnSizeChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


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
| **NumberBoxElement** | StiNumberBoxElement |  |

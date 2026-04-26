---
title: "StiCloudPlan Class"
---

## StiCloudPlan Class

**Namespace:** `Stimulsoft.Base.Plans`

### Inheritance

Inherits from: [StiPlan](StiPlan.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowDataTransformation** | bool |  |
| **AllowDatabases** | bool |  |
| **MaxDataRows** | int |  |
| **MaxFileSize** | int |  |
| **MaxItems** | int? |  |
| **MaxRefreshes** | int |  |
| **MaxReportPages** | int |  |
| **MaxResourceSize** | int |  |
| **MaxResources** | int |  |
| **MaxViewers** | int? |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetPlan** `static` *(+2 overloads)* | [StiCloudPlan](StiCloudPlan.md) |  |
| **GetPlanIdent** `static` | [StiCloudPlanIdent](StiCloudPlanIdent.md) |  |
| **IsAppsAvailable** `static` | bool |  |
| **IsDashboardsAvailable** `static` | bool |  |
| **IsFormsAvailable** `static` | bool |  |
| **IsReportsAvailable** `static` | bool |  |
| **IsTrial** `static` | bool |  |
| **SetPlan** `static` | void |  |

---

### Method Details

#### GetPlan `static`

**GetPlan**(**reportGuid**: string): [StiCloudPlan](StiCloudPlan.md)

**Parameters**

- **reportGuid** (string)  

**Returns** [StiCloudPlan](StiCloudPlan.md)

---

**GetPlan**(**licenceKey**: [StiLicenseKey](../Licenses/StiLicenseKey.md)): [StiCloudPlan](StiCloudPlan.md)

**Parameters**

- **licenceKey** ([StiLicenseKey](../Licenses/StiLicenseKey.md))  

**Returns** [StiCloudPlan](StiCloudPlan.md)

---

**GetPlan**(**ident**: [StiCloudPlanIdent](StiCloudPlanIdent.md)): [StiCloudPlan](StiCloudPlan.md)

**Parameters**

- **ident** ([StiCloudPlanIdent](StiCloudPlanIdent.md))  

**Returns** [StiCloudPlan](StiCloudPlan.md)


---

#### GetPlanIdent `static`

**GetPlanIdent**(**reportGuid**: string): [StiCloudPlanIdent](StiCloudPlanIdent.md)

**Parameters**

- **reportGuid** (string)  

**Returns** [StiCloudPlanIdent](StiCloudPlanIdent.md)


---

#### IsAppsAvailable `static`

**IsAppsAvailable**(**reportGuid**: string): bool

**Parameters**

- **reportGuid** (string)  

**Returns** bool


---

#### IsDashboardsAvailable `static`

**IsDashboardsAvailable**(**reportGuid**: string): bool

**Parameters**

- **reportGuid** (string)  

**Returns** bool


---

#### IsFormsAvailable `static`

**IsFormsAvailable**(**reportGuid**: string): bool

**Parameters**

- **reportGuid** (string)  

**Returns** bool


---

#### IsReportsAvailable `static`

**IsReportsAvailable**(**reportGuid**: string): bool

**Parameters**

- **reportGuid** (string)  

**Returns** bool


---

#### IsTrial `static`

**IsTrial**(**reportGuid**: string): bool

**Parameters**

- **reportGuid** (string)  

**Returns** bool


---

#### SetPlan `static`

**SetPlan**(**reportGuid**: string, **plan**: [StiCloudPlanIdent](StiCloudPlanIdent.md)): void

**Parameters**

- **reportGuid** (string)  
- **plan** ([StiCloudPlanIdent](StiCloudPlanIdent.md))  


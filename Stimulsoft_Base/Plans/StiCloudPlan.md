---
title: "StiCloudPlan Class"
---

## StiCloudPlan Class

**Namespace:** `Stimulsoft.Base.Plans`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class StiCloudPlan
```

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

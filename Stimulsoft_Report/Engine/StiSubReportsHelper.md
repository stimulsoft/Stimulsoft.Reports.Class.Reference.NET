---
title: "StiSubReportsHelper Class"
---

## StiSubReportsHelper Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

A class helps to render SubReport and DataBand components which are places in containers. These containers are placed on bands.

```csharp
public class StiSubReportsHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **RenderExternalSubReportsWithoutHelpOfUnlimitedHeightPagesOldMode** `static` | bool | Is used for backward compatibility with 2019.x if RenderExternalSubReportsWithHelpOfUnlimitedHeightPages=false |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMasterDataBand** `static` | StiDataBand | Returns DataBand which is one of Parent components of the specified container. |
| **GetParentBand** `static` | StiBand | Returns Band which is one of Parent components of the specified container. |
| **RenderDataBandsInContainer** `static` | void | Prints a group of bands from the specified container into the container of destination. |
| **RenderSubReport** `static` | void | Prints SubReport component into the specified container. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SpecialSubReportHeight** | double |  |

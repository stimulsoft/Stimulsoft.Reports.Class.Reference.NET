---
title: "StiSubReportsHelper Class"
---

## StiSubReportsHelper Class

**Namespace:** `Stimulsoft.Report.Engine`

A class helps to render SubReport and DataBand components which are places in containers. These containers are placed on bands.

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

---

### Method Details

#### GetMasterDataBand `static`

**GetMasterDataBand**(**parent**: StiContainer): StiDataBand

Returns DataBand which is one of Parent components of the specified container.

**Parameters**

- **parent** (StiContainer)  

**Returns** StiDataBand


---

#### GetParentBand `static`

**GetParentBand**(**parent**: StiContainer): StiBand

Returns Band which is one of Parent components of the specified container.

**Parameters**

- **parent** (StiContainer)  

**Returns** StiBand


---

#### RenderDataBandsInContainer `static`

**RenderDataBandsInContainer**(**containerOfDataBands**: StiContainer, **container**: StiContainer): void

Prints a group of bands from the specified container into the container of destination.

**Parameters**

- **containerOfDataBands** (StiContainer) — A container in what printing is done.  
- **container** (StiContainer) — A container that contains a group of bands.  


---

#### RenderSubReport `static`

**RenderSubReport**(**containerOfSubReport**: StiContainer, **subReport**: [StiSubReport](../Components/StiSubReport.md)): void

Prints SubReport component into the specified container.

**Parameters**

- **containerOfSubReport** (StiContainer) — A container in what the SubReport should be printed.  
- **subReport** ([StiSubReport](../Components/StiSubReport.md)) — SubReport that should be printed in the specified container.  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SpecialSubReportHeight** | double |  |

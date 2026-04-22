---
title: "StiTableColumnDashboardInteraction Class"
---

## StiTableColumnDashboardInteraction Class

**Namespace:** `Stimulsoft.Dashboard.Interactions`  
**Assembly:** `Stimulsoft.Dashboard`

Describes an interaction functionality of the table column.

```csharp
public class StiTableColumnDashboardInteraction
```

### Inheritance

Inherits from: StiDashboardInteraction  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableColumnDashboardInteraction**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Ident** | [StiInteractionIdent](../../Stimulsoft_Report/Dashboard/StiInteractionIdent.md) | ID code of this interaction. Used in JSON saving. |
| **OnClick** | [StiInteractionOnClick](../../Stimulsoft_Report/Dashboard/StiInteractionOnClick.md) |  |
| **OnHover** | [StiInteractionOnHover](../../Stimulsoft_Report/Dashboard/StiInteractionOnHover.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ShouldSerializeOnClick** | bool |  |
| **ShouldSerializeOnHover** | bool |  |

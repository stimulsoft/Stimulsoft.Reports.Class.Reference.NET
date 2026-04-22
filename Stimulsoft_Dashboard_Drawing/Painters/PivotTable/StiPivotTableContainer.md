---
title: "StiPivotTableContainer Class"
---

## StiPivotTableContainer Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters.PivotTable`  
**Assembly:** `Stimulsoft.Dashboard.Drawing`

```csharp
public class StiPivotTableContainer
```

### Inheritance

Implements: [IStiPivotGridContainer](../../../Stimulsoft_Report/Dashboard/IStiPivotGridContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPivotTableContainer(Control control, StiPivotTableElement element)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | Control |  |
| **HeaderHeight** | int |  |
| **HeaderWidth** | int |  |
| **Height** | double |  |
| **OnlySummaries** | bool |  |
| **Width** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **ExpandCollapse** | void |  |
| **FindSelectableCell** | [StiPivotTableCell](StiPivotTableCell.md) |  |
| **GetParent** | [StiPivotTableCell](StiPivotTableCell.md) |  |
| **GridPaint** | void |  |
| **MakeGrid** | void |  |
| **OnMouseMove** | void |  |
| **OpenLink** | void |  |
| **OpenNewTab** | void |  |
| **RestoreState** | void |  |
| **SaveState** | void |  |
| **UpdateSize** | void |  |
| **UpdateWidthAndHeight** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **AfterSizeUpdate** | EventHandler |  |
| **NewTab** | StiValueEventHandler |  |
| **OpenLinkHandler** | StiValueEventHandler |  |
| **TooltipHandler** | StiPivotTableElementTooltipEvenHandler |  |

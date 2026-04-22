---
title: "StiTableElementSortFilterMenu Class"
---

## StiTableElementSortFilterMenu Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.Table.Menu`  
**Assembly:** `Stimulsoft.Dashboard.Viewer`

```csharp
public class StiTableElementSortFilterMenu
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColumnKey** | string |  |
| **ColumnPath** | string |  |
| **ColumnType** | Type |  |
| **FilterItems** | List<[StiTableElementSortFilterMenuItem](StiTableElementSortFilterMenuItem.md)> |  |
| **Menu** | ContextMenuStrip |  |
| **ParentForm** | Form |  |
| **PrimaryKey** | bool |  |
| **Restrictions** | [StiDataTransformationRestrictions](../../../StiDataTransformationRestrictions.md) |  |
| **TableElement** | IStiTableElement |  |
| **TableView** | [StiTableViewControl](../StiTableViewControl.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateFilterMenuItems** | void |  |
| **CreateItems** | void |  |
| **CreateMenuItems** | void |  |
| **CreateSortMenuItems** | void |  |
| **GetFilterStringItems** | List<string> |  |
| **IsAllowed** | bool |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **FiltersChanged** | EventHandler |  |
| **SortChanged** | EventHandler |  |

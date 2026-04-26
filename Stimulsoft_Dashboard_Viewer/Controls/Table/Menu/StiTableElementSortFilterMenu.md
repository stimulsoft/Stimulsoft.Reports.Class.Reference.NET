---
title: "StiTableElementSortFilterMenu Class"
---

## StiTableElementSortFilterMenu Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.Table.Menu`

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
| **Restrictions** | [StiDataTransformationRestrictions](../../../root/StiDataTransformationRestrictions.md) |  |
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

---

### Method Details

#### CreateFilterMenuItems

**CreateFilterMenuItems**(): void


---

#### CreateItems

**CreateItems**(**meters**: List<[IStiMeter](../../../../Stimulsoft_Base/Meters/IStiMeter.md)>, **columnIndex**: int, **element**: IStiTableElement): void

**Parameters**

- **meters** (List<[IStiMeter](../../../../Stimulsoft_Base/Meters/IStiMeter.md)>)  
- **columnIndex** (int)  
- **element** (IStiTableElement)  


---

#### CreateMenuItems

**CreateMenuItems**(**element**: IStiTableElement, **allowInteractive**: bool): void

**Parameters**

- **element** (IStiTableElement)  
- **allowInteractive** (bool)  


---

#### CreateSortMenuItems

**CreateSortMenuItems**(): void


---

#### GetFilterStringItems

**GetFilterStringItems**(): List<string>

**Returns** List<string>


---

#### IsAllowed

**IsAllowed**(**restriction**: [StiDataTransformationRestrictions](../../../root/StiDataTransformationRestrictions.md)): bool

**Parameters**

- **restriction** ([StiDataTransformationRestrictions](../../../root/StiDataTransformationRestrictions.md))  

**Returns** bool


### Events

| Event | Type | Description |
| --- | --- | --- |
| **FiltersChanged** | EventHandler |  |
| **SortChanged** | EventHandler |  |

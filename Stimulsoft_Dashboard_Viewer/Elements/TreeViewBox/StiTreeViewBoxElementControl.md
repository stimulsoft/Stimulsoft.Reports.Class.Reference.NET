---
title: "StiTreeViewBoxElementControl Class"
---

## StiTreeViewBoxElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.TreeViewBox`

### Inheritance

Inherits from: StiFilterElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreeViewBoxElementControl**(IStiElement element) |  |

**StiTreeViewBoxElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFullPathNodes** | List<[StiTreeNode](../../Controls/TreeView/StiTreeNode.md)> |  |
| **OnSizeChanged** | void |  |
| **RefreshChild** | void |  |
| **SetDefaultSelection** | void |  |
| **UpdateSelectionProps** | void |  |

---

### Method Details

#### GetFullPathNodes

**GetFullPathNodes**(**node**: [StiTreeNode](../../Controls/TreeView/StiTreeNode.md), **isFullPath**: bool): List<[StiTreeNode](../../Controls/TreeView/StiTreeNode.md)>

**Parameters**

- **node** ([StiTreeNode](../../Controls/TreeView/StiTreeNode.md))  
- **isFullPath** (bool)  

**Returns** List<[StiTreeNode](../../Controls/TreeView/StiTreeNode.md)>


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

#### SetDefaultSelection

**SetDefaultSelection**(**lockRefresh**: bool): void

**Parameters**

- **lockRefresh** (bool)  


---

#### UpdateSelectionProps

**UpdateSelectionProps**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ShowAllValue** | bool |  |
| **TreeViewBoxControl** | [StiTreeViewBox](../../Controls/TreeView/StiTreeViewBox.md) |  |
| **TreeViewBoxElement** | StiTreeViewBoxElement |  |

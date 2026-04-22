---
title: "StiDataBuilder Class"
---

## StiDataBuilder Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Used to build trees by the data source.

```csharp
public class StiDataBuilder
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiDataBuilder()` | Creates a new object of the type StiDataBuilder. |
| `StiDataBuilder([StiTreeView](../../Stimulsoft_Dashboard_Viewer/Controls/TreeView/StiTreeView.md) treeView)` | Creates a new object of the type StiDataBuilder. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ShowParameters** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BuildBusinessObject** | void | Builds TreeNode from the Business Object. |
| **CheckBusinessObject** | bool |  |
| **CollapsedNode** | void |  |
| **ExpandedNode** *(+3 overloads)* | void |  |
| **GetColumnPathFromNode** `static` *(+1 overloads)* | string | Returns the ColumnPath from TreeNode. |
| **GetColumnPathFromNodeWithAlias** `static` | string | Returns the string view of a column from TreeNode taking into consideration aliases. |
| **GetColumnPathFromNodeWithAliasWithoutReplace** `static` | string |  |
| **GetDataBandColumnPathFromNode** `static` | string | Returns the ColumnPath from TreeNode for Interaction. |
| **GetParameterPathFromNode** `static` | string |  |
| **GetPropertyInfoPathFromNode** `static` | string | Returns the PropertyInfoPath from TreeNode. |

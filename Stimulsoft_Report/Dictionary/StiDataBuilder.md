---
title: "StiDataBuilder Class"
---

## StiDataBuilder Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Used to build trees by the data source.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataBuilder**() | Creates a new object of the type StiDataBuilder. |
| **StiDataBuilder**([StiTreeView](../../Stimulsoft_Dashboard_Viewer/Controls/TreeView/StiTreeView.md) treeView) | Creates a new object of the type StiDataBuilder. |

**StiDataBuilder**()

Creates a new object of the type StiDataBuilder.

---

**StiDataBuilder**(**treeView**: [StiTreeView](../../Stimulsoft_Dashboard_Viewer/Controls/TreeView/StiTreeView.md))

Creates a new object of the type StiDataBuilder.

**Parameters**

- **treeView** ([StiTreeView](../../Stimulsoft_Dashboard_Viewer/Controls/TreeView/StiTreeView.md))  


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

---

### Method Details

#### BuildBusinessObject

**BuildBusinessObject**(**businessObject**: StiBusinessObject, **parentNode**: TreeNode, **includeColumns**: bool, **includeCalcColumns**: bool): void

Builds TreeNode from the Business Object.

**Parameters**

- **businessObject** (StiBusinessObject)  
- **parentNode** (TreeNode)  
- **includeColumns** (bool)  
- **includeCalcColumns** (bool)  


---

#### CheckBusinessObject

**CheckBusinessObject**(**businessObject**: StiBusinessObject, **includeColumns**: bool, **includeCalcColumns**: bool): bool

**Parameters**

- **businessObject** (StiBusinessObject)  
- **includeColumns** (bool)  
- **includeCalcColumns** (bool)  

**Returns** bool


---

#### CollapsedNode

**CollapsedNode**(**node**: TreeNode): void

**Parameters**

- **node** (TreeNode)  


---

#### ExpandedNode

**ExpandedNode**(**node**: [TreeNodeEx](TreeNodeEx.md), **includeCalcColumn**: bool): void

**Parameters**

- **node** ([TreeNodeEx](TreeNodeEx.md))  
- **includeCalcColumn** (bool)  

---

**ExpandedNode**(**node**: [TreeNodeEx](TreeNodeEx.md), **includeColumn**: bool, **includeCalcColumn**: bool): void

**Parameters**

- **node** ([TreeNodeEx](TreeNodeEx.md))  
- **includeColumn** (bool)  
- **includeCalcColumn** (bool)  

---

**ExpandedNode**(**node**: [TreeNodeEx](TreeNodeEx.md), **includeCalcColumn**: bool, **tag**: object): void

**Parameters**

- **node** ([TreeNodeEx](TreeNodeEx.md))  
- **includeCalcColumn** (bool)  
- **tag** (object)  

---

**ExpandedNode**(**node**: [TreeNodeEx](TreeNodeEx.md), **includeColumn**: bool, **includeCalcColumn**: bool, **tag**: object): void

**Parameters**

- **node** ([TreeNodeEx](TreeNodeEx.md))  
- **includeColumn** (bool)  
- **includeCalcColumn** (bool)  
- **tag** (object)  


---

#### GetColumnPathFromNode `static`

**GetColumnPathFromNode**(**node**: TreeNode): string

Returns the ColumnPath from TreeNode.

**Parameters**

- **node** (TreeNode) — TreeNode to build the string view of a column.  

**Returns** string — ColumnPath.

---

**GetColumnPathFromNode**(**node**: TreeNode, **useRelationName**: bool, **isDataExpression**: bool): string

Returns the ColumnPath from TreeNode.

**Parameters**

- **node** (TreeNode) — TreeNode to build the string view of a column.  
- **useRelationName** (bool)  
- **isDataExpression** (bool)  

**Returns** string — ColumnPath.


---

#### GetColumnPathFromNodeWithAlias `static`

**GetColumnPathFromNodeWithAlias**(**node**: TreeNode): string

Returns the string view of a column from TreeNode taking into consideration aliases.

**Parameters**

- **node** (TreeNode) — TreeNode to build the string view of a column.  

**Returns** string


---

#### GetColumnPathFromNodeWithAliasWithoutReplace `static`

**GetColumnPathFromNodeWithAliasWithoutReplace**(**node**: TreeNode): string

**Parameters**

- **node** (TreeNode)  

**Returns** string


---

#### GetDataBandColumnPathFromNode `static`

**GetDataBandColumnPathFromNode**(**node**: TreeNode, **useRelationName**: bool): string

Returns the ColumnPath from TreeNode for Interaction.

**Parameters**

- **node** (TreeNode) — TreeNode to build the string view of a column.  
- **useRelationName** (bool)  

**Returns** string — ColumnPath.


---

#### GetParameterPathFromNode `static`

**GetParameterPathFromNode**(**node**: TreeNode): string

**Parameters**

- **node** (TreeNode)  

**Returns** string


---

#### GetPropertyInfoPathFromNode `static`

**GetPropertyInfoPathFromNode**(**node**: TreeNode): string

Returns the PropertyInfoPath from TreeNode.

**Parameters**

- **node** (TreeNode) — TreeNode to build the string view of a PropertyInfo.  

**Returns** string — PropertyInfoPath.


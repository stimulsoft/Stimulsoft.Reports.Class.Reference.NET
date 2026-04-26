---
title: "StiTreeView Class"
---

## StiTreeView Class

**Namespace:** `Stimulsoft.Report.Controls`

### Inheritance

Inherits from: TreeView  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Lock** | void | Disables any updating of the tree view. |
| **OnClick** | void |  |
| **OnDrawNode** | void |  |
| **OnHandleCreated** | void |  |
| **SetBold** *(+1 overloads)* | void | Sets specified TreeNode Bold mode. |
| **Unlock** | void | Enables the updating of the tree view. |
| **WndProc** | void |  |

---

### Method Details

#### Lock

**Lock**(): void

Disables any updating of the tree view.


---

#### OnClick

**OnClick**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnDrawNode

**OnDrawNode**(**e**: [StiDrawTreeNodeEventArgs](StiDrawTreeNodeEventArgs.md)): void

**Parameters**

- **e** ([StiDrawTreeNodeEventArgs](StiDrawTreeNodeEventArgs.md))  


---

#### OnHandleCreated

**OnHandleCreated**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### SetBold

**SetBold**(**node**: TreeNode, **isBold**: bool): void

Sets specified TreeNode Bold mode.

**Parameters**

- **node** (TreeNode) — Specified TreeNode.  
- **isBold** (bool) — Bold mode.  

---

**SetBold**(**treeView**: TreeView, **node**: TreeNode, **isBold**: bool): void

Sets specified TreeNode Bold mode.

**Parameters**

- **treeView** (TreeView)  
- **node** (TreeNode) — Specified TreeNode.  
- **isBold** (bool) — Bold mode.  


---

#### Unlock

**Unlock**(): void

Enables the updating of the tree view.


---

#### WndProc

**WndProc**(**msg**: Message): void

**Parameters**

- **msg** (Message)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **DrawNode** | StiDrawTreeNodeEventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **cChildren** | int |  |
| **cchTextMax** | int |  |
| **hItem** | IntPtr |  |
| **iImage** | int |  |
| **iIntegral** | int |  |
| **iSelectedImage** | int |  |
| **lParam** | IntPtr |  |
| **mask** | int |  |
| **pszText** | string |  |
| **state** | int |  |
| **stateMask** | int |  |

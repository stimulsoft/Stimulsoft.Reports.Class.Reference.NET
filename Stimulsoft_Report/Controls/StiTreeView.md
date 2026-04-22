---
title: "StiTreeView Class"
---

## StiTreeView Class

**Namespace:** `Stimulsoft.Report.Controls`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiTreeView
```

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

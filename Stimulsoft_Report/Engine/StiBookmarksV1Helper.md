---
title: "StiBookmarksV1Helper Class"
---

## StiBookmarksV1Helper Class

**Namespace:** `Stimulsoft.Report.Engine`

A class that helps with bookmarks.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | void |  |
| **AddBookmarks** `static` | void |  |
| **CreateBookmark** `static` *(+1 overloads)* | [StiBookmark](../Components/StiBookmark.md) | Creates a new bookmark. |
| **GetBookmark** `static` | [StiBookmark](../Components/StiBookmark.md) |  |
| **GetTreeNode** `static` | TreeNode | Returns an object of the TreeNode type from the StiBookmark object. |
| **Pack** `static` | void |  |
| **PrepareBookmark** `static` | void | Prepares a bookmark and all of its child bookmarks for showing. |

---

### Method Details

#### Add `static`

**Add**(**bookmark**: [StiBookmark](../Components/StiBookmark.md), **name**: string): void

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  
- **name** (string)  


---

#### AddBookmarks `static`

**AddBookmarks**(**bookmark**: [StiBookmark](../Components/StiBookmark.md), **treeNode**: TreeNode): void

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  
- **treeNode** (TreeNode)  


---

#### CreateBookmark `static`

**CreateBookmark**(**text**: string, **parentComponent**: object): [StiBookmark](../Components/StiBookmark.md)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  
- **parentComponent** (object)  

**Returns** [StiBookmark](../Components/StiBookmark.md)

---

**CreateBookmark**(**text**: string, **bookmarkText**: string, **parentComponent**: object): [StiBookmark](../Components/StiBookmark.md)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  
- **bookmarkText** (string) — Boormark text.  
- **parentComponent** (object)  

**Returns** [StiBookmark](../Components/StiBookmark.md)


---

#### GetBookmark `static`

**GetBookmark**(**bookmark**: [StiBookmark](../Components/StiBookmark.md), **name**: string): [StiBookmark](../Components/StiBookmark.md)

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  
- **name** (string)  

**Returns** [StiBookmark](../Components/StiBookmark.md)


---

#### GetTreeNode `static`

**GetTreeNode**(**bookmark**: [StiBookmark](../Components/StiBookmark.md)): TreeNode

Returns an object of the TreeNode type from the StiBookmark object.

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md)) — StiBookmark to form TreeNode.  

**Returns** TreeNode — Formed TreeNode.


---

#### Pack `static`

**Pack**(**bookmark**: [StiBookmark](../Components/StiBookmark.md)): void

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  


---

#### PrepareBookmark `static`

**PrepareBookmark**(**bookmark**: [StiBookmark](../Components/StiBookmark.md)): void

Prepares a bookmark and all of its child bookmarks for showing.

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md)) — Bookmark for preparing.  


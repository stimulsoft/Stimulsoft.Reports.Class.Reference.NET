---
title: "StiBookmarksV2Helper Class"
---

## StiBookmarksV2Helper Class

**Namespace:** `Stimulsoft.Report.Engine`

A class helps with bookmarks.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | void | Adds a bookmark manually. When adding the IsManualBookmark flag is set. This flag gives a signal to the report generator that search should be done in a reductive mode (direct comparison of BookmarkValue). |
| **CreateBookmark** `static` *(+1 overloads)* | [StiBookmark](../Components/StiBookmark.md) | Creates a new bookmark. |
| **GetBookmark** `static` | [StiBookmark](../Components/StiBookmark.md) |  |
| **GetTreeNodeFromBookmarks** `static` | TreeNode | Returns an object of the TreeNode type from the StiBookmark object. |
| **Pack** `static` | void |  |
| **PrepareBookmark** `static` | void | Prepares a bookmark and all of its child bookmarks for showing. |

---

### Method Details

#### Add `static`

**Add**(**bookmark**: [StiBookmark](../Components/StiBookmark.md), **name**: string): void

Adds a bookmark manually. When adding the IsManualBookmark flag is set. This flag gives a signal to the report generator that search should be done in a reductive mode (direct comparison of BookmarkValue).

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  
- **name** (string)  


---

#### CreateBookmark `static`

**CreateBookmark**(**text**: string): [StiBookmark](../Components/StiBookmark.md)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  

**Returns** [StiBookmark](../Components/StiBookmark.md)

---

**CreateBookmark**(**text**: string, **componentGuid**: string): [StiBookmark](../Components/StiBookmark.md)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  
- **componentGuid** (string)  

**Returns** [StiBookmark](../Components/StiBookmark.md)


---

#### GetBookmark `static`

**GetBookmark**(**bookmark**: [StiBookmark](../Components/StiBookmark.md), **name**: string): [StiBookmark](../Components/StiBookmark.md)

**Parameters**

- **bookmark** ([StiBookmark](../Components/StiBookmark.md))  
- **name** (string)  

**Returns** [StiBookmark](../Components/StiBookmark.md)


---

#### GetTreeNodeFromBookmarks `static`

**GetTreeNodeFromBookmarks**(**bookmark**: [StiBookmark](../Components/StiBookmark.md)): TreeNode

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


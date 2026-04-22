---
title: "StiBookmarksV2Helper Class"
---

## StiBookmarksV2Helper Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

A class helps with bookmarks.

```csharp
public sealed class StiBookmarksV2Helper
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | void | Adds a bookmark manually. When adding the IsManualBookmark flag is set. This flag gives a signal to the report generator that search should be done in a reductive mode (direct comparison of BookmarkValue). |
| **CreateBookmark** `static` *(+1 overloads)* | [StiBookmark](../Components/StiBookmark.md) | Creates a new bookmark. |
| **GetBookmark** `static` | [StiBookmark](../Components/StiBookmark.md) |  |
| **GetTreeNodeFromBookmarks** `static` | TreeNode | Returns an object of the TreeNode type from the StiBookmark object. |
| **Pack** `static` | void |  |
| **PrepareBookmark** `static` | void | Prepares a bookmark and all of its child bookmarks for showing. |

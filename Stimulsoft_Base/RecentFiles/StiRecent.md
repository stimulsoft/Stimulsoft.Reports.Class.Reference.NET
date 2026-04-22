---
title: "StiRecent Class"
---

## StiRecent Class

**Namespace:** `Stimulsoft.Base.RecentFiles`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiRecent
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Current** `static` | [StiRecent](StiRecent.md) |  |
| **Folders** | List<[StiRecentFolder](StiRecentFolder.md)> |  |
| **FoldersNewMode** | bool |  |
| **LocalDefaultFolder** | string |  |
| **LocalDefaultFolder** | string |  |
| **SaveAsDefaultFolder** | string |  |
| **SaveAsDefaultFolder** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddCloudFile** | void |  |
| **AddCloudFolder** | void |  |
| **AddGoogleDriveFile** | void |  |
| **AddLocalFile** *(+1 overloads)* | void |  |
| **AddLocalFolder** | void |  |
| **MoveToTop** | void |  |
| **RemoveAllFile** | void |  |
| **RemoveFile** | void |  |
| **RemoveFolder** | void |  |
| **Save** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **CloudFolderChanged** | StiRecentCloudFolderChangedEventHandler |  |
| **RecentFilesChanged** | EventHandler |  |
| **RecentFoldersChanged** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **RecentFiles** | [StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md)[] |  |
| **RecentFolders** | [StiRecentFolder](StiRecentFolder.md)[] |  |

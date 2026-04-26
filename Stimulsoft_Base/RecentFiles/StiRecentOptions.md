---
title: "StiRecentOptions Class"
---

## StiRecentOptions Class

**Namespace:** `Stimulsoft.Base.RecentFiles`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ShowCopyPathToClipboardInContextMenu** `static` | bool |  |
| **ShowDeleteFileInContextMenu** `static` | bool |  |
| **ShowOnlyExistingRecentFiles** `static` | bool |  |
| **ShowOpenContainingFolderInContextMenu** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InvokeDisplayRecentFileInDesigner** `static` | [StiDisplayRecentFileEventArgs](StiDisplayRecentFileEventArgs.md) |  |

---

### Method Details

#### InvokeDisplayRecentFileInDesigner `static`

**InvokeDisplayRecentFileInDesigner**(**designer**: object, **recentFile**: [StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md)): [StiDisplayRecentFileEventArgs](StiDisplayRecentFileEventArgs.md)

**Parameters**

- **designer** (object)  
- **recentFile** ([StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md))  

**Returns** [StiDisplayRecentFileEventArgs](StiDisplayRecentFileEventArgs.md)


### Events

| Event | Type | Description |
| --- | --- | --- |
| **DisplayRecentFileInDesigner** | StiDisplayRecentFileEventHandler |  |
| **OpenRecentFileInDesigner** | StiOpenRecentFileInDesignerEventHandler |  |

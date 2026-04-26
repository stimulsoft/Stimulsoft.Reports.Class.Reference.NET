---
title: "StiRecent Class"
---

## StiRecent Class

**Namespace:** `Stimulsoft.Base.RecentFiles`

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

---

### Method Details

#### AddCloudFile

**AddCloudFile**(**name**: string, **itemKey**: string, **folderKey**: string, **path**: string, **isPinned**: bool, **addFirst**: bool, **autoSave**: bool): void

**Parameters**

- **name** (string)  
- **itemKey** (string)  
- **folderKey** (string)  
- **path** (string)  
- **isPinned** (bool)  
- **addFirst** (bool)  
- **autoSave** (bool)  


---

#### AddCloudFolder

**AddCloudFolder**(**name**: string, **itemKey**: string, **path**: string, **isPinned**: bool, **addFirst**: bool, **autoSave**: bool): void

**Parameters**

- **name** (string)  
- **itemKey** (string)  
- **path** (string)  
- **isPinned** (bool)  
- **addFirst** (bool)  
- **autoSave** (bool)  


---

#### AddGoogleDriveFile

**AddGoogleDriveFile**(**name**: string, **itemKey**: string, **path**: string, **isPinned**: bool, **addFirst**: bool, **autoSave**: bool): void

**Parameters**

- **name** (string)  
- **itemKey** (string)  
- **path** (string)  
- **isPinned** (bool)  
- **addFirst** (bool)  
- **autoSave** (bool)  


---

#### AddLocalFile

**AddLocalFile**(**filePath**: string, **isPinned**: bool, **addFirst**: bool, **autoSave**: bool, **tag**: object): void

**Parameters**

- **filePath** (string)  
- **isPinned** (bool)  
- **addFirst** (bool)  
- **autoSave** (bool)  
- **tag** (object)  

---

**AddLocalFile**(**filePath**: string, **isPinned**: bool, **dateModified**: DateTime, **addFirst**: bool, **autoSave**: bool, **tag**: object): void

**Parameters**

- **filePath** (string)  
- **isPinned** (bool)  
- **dateModified** (DateTime)  
- **addFirst** (bool)  
- **autoSave** (bool)  
- **tag** (object)  


---

#### AddLocalFolder

**AddLocalFolder**(**folderPath**: string, **isPinned**: bool, **addFirst**: bool, **autoSave**: bool): void

**Parameters**

- **folderPath** (string)  
- **isPinned** (bool)  
- **addFirst** (bool)  
- **autoSave** (bool)  


---

#### MoveToTop

**MoveToTop**(**file**: [StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md)): void

**Parameters**

- **file** ([StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md))  


---

#### RemoveAllFile

**RemoveAllFile**(**runEvent**: bool): void

**Parameters**

- **runEvent** (bool)  


---

#### RemoveFile

**RemoveFile**(**file**: [StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md), **runEvent**: bool): void

**Parameters**

- **file** ([StiRecentFile](../../Stimulsoft_Report/Design/StiRecentFile.md))  
- **runEvent** (bool)  


---

#### RemoveFolder

**RemoveFolder**(**folder**: [StiRecentFolder](StiRecentFolder.md)): void

**Parameters**

- **folder** ([StiRecentFolder](StiRecentFolder.md))  


---

#### Save

**Save**(): void


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

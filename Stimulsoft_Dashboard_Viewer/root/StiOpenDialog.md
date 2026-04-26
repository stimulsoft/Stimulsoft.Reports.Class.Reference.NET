---
title: "StiOpenDialog Class"
---

## StiOpenDialog Class

**Namespace:** `Stimulsoft.Dashboard.Viewer`

### Inheritance

Implements: [IStiViewerOpenDialog](../../Stimulsoft_Base/Viewer/IStiViewerOpenDialog.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOpenDialog**([StiDashboardViewerControl](StiDashboardViewerControl.md) viewerControl) |  |

**StiOpenDialog**(**viewerControl**: [StiDashboardViewerControl](StiDashboardViewerControl.md))

**Parameters**

- **viewerControl** ([StiDashboardViewerControl](StiDashboardViewerControl.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Run** *(+1 overloads)* | void |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### Run

**Run**(**openDialog**: bool, **fileName**: string, **clearAfter**: bool, **ownerObj**: object): void

**Parameters**

- **openDialog** (bool)  
- **fileName** (string)  
- **clearAfter** (bool)  
- **ownerObj** (object)  

---

**Run**(**openDialog**: bool, **fileName**: string, **clearAfter**: bool, **owner**: IWin32Window): void

**Parameters**

- **openDialog** (bool)  
- **fileName** (string)  
- **clearAfter** (bool)  
- **owner** (IWin32Window)  


---
title: "StiHtmlTableRender Class"
---

## StiHtmlTableRender Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **RenderStyle** | void |  |
| **RenderStyleTable** | void |  |
| **RenderStyles** *(+1 overloads)* | void |  |
| **RenderStylesTable** *(+4 overloads)* | void |  |
| **RenderTable** | void |  |

---

### Method Details

#### RenderStyle

**RenderStyle**(**style**: [StiCellStyle](StiCellStyle.md)): void

**Parameters**

- **style** ([StiCellStyle](StiCellStyle.md))  


---

#### RenderStyleTable

**RenderStyleTable**(**cell**: [StiHtmlTableCell](StiHtmlTableCell.md), **style**: [StiCellStyle](StiCellStyle.md)): void

**Parameters**

- **cell** ([StiHtmlTableCell](StiHtmlTableCell.md))  
- **style** ([StiCellStyle](StiCellStyle.md))  


---

#### RenderStyles

**RenderStyles**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **cssStyles**: Hashtable, **nonce**: string): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **cssStyles** (Hashtable)  
- **nonce** (string)  

---

**RenderStyles**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **cssStyles**: Hashtable, **cssClass**: string, **nonce**: string): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **cssStyles** (Hashtable)  
- **cssClass** (string)  
- **nonce** (string)  


---

#### RenderStylesTable

**RenderStylesTable**(**useBookmarks**: bool, **exportBookmarksOnly**: bool): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  

---

**RenderStylesTable**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **addStyleTag**: bool): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **addStyleTag** (bool)  

---

**RenderStylesTable**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **cssStyles**: Hashtable): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **cssStyles** (Hashtable)  

---

**RenderStylesTable**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **addStyleTag**: bool, **cssStyles**: Hashtable): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **addStyleTag** (bool)  
- **cssStyles** (Hashtable)  

---

**RenderStylesTable**(**useBookmarks**: bool, **exportBookmarksOnly**: bool, **addStyleTag**: bool, **cssStyles**: Hashtable, **cssClass**: string, **nonce**: string): void

**Parameters**

- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **addStyleTag** (bool)  
- **cssStyles** (Hashtable)  
- **cssClass** (string)  
- **nonce** (string)  


---

#### RenderTable

**RenderTable**(**renderStyles**: bool, **backGroundImageString**: string, **useBookmarks**: bool, **exportBookmarksOnly**: bool, **cssStyles**: Hashtable, **watermarkShowBehind**: bool, **border**: StiBorder): void

**Parameters**

- **renderStyles** (bool)  
- **backGroundImageString** (string)  
- **useBookmarks** (bool)  
- **exportBookmarksOnly** (bool)  
- **cssStyles** (Hashtable)  
- **watermarkShowBehind** (bool)  
- **border** (StiBorder)  


---
title: "StiTableOfContentsV2Builder Class"
---

## StiTableOfContentsV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiDataBandV2Builder](StiDataBandV2Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | StiComponent |  |
| **PostProcessBookmarks** `static` *(+1 overloads)* | void |  |

---

### Method Details

#### InternalRender

**InternalRender**(**masterComp**: StiComponent): StiComponent

**Parameters**

- **masterComp** (StiComponent)  

**Returns** StiComponent


---

#### PostProcessBookmarks `static`

**PostProcessBookmarks**(**comps**: List<StiComponent>, **masterComp**: [StiTableOfContents](../Components/StiTableOfContents.md), **resultComp**: StiComponent): void

**Parameters**

- **comps** (List<StiComponent>)  
- **masterComp** ([StiTableOfContents](../Components/StiTableOfContents.md))  
- **resultComp** (StiComponent)  

---

**PostProcessBookmarks**(**comps**: List<StiComponent>, **baseName**: string, **panel**: StiComponent, **bookmarks**: StiBookmarksCollection): void

**Parameters**

- **comps** (List<StiComponent>)  
- **baseName** (string)  
- **panel** (StiComponent)  
- **bookmarks** (StiBookmarksCollection)  


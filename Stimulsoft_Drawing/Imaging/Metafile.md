---
title: "Metafile Class"
---

## Metafile Class

**Namespace:** `Stimulsoft.Drawing.Imaging`

### Inheritance

Implements: [Image](../root/Image.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Metafile**(IntPtr referenceHdc, System.Drawing.Imaging.EmfType emfType) |  |
| **Metafile**(Stream stream, IntPtr referenceHdc) |  |
| **Metafile**(IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type) |  |
| **Metafile**(Stream stream, IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit) |  |
| **Metafile**(Stream stream, IntPtr referenceHdc, object p, System.Drawing.Imaging.MetafileFrameUnit pixel) |  |
| **Metafile**(IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type, string description) |  |
| **Metafile**(Stream stream, IntPtr referenceHdc, RectangleF frameRect, System.Drawing.Imaging.MetafileFrameUnit frameUnit, System.Drawing.Imaging.EmfType type, string description) |  |

**Metafile**(**referenceHdc**: IntPtr, **emfType**: System.Drawing.Imaging.EmfType)

**Parameters**

- **referenceHdc** (IntPtr)  
- **emfType** (System.Drawing.Imaging.EmfType)  

---

**Metafile**(**stream**: Stream, **referenceHdc**: IntPtr)

**Parameters**

- **stream** (Stream)  
- **referenceHdc** (IntPtr)  

---

**Metafile**(**referenceHdc**: IntPtr, **frameRect**: RectangleF, **frameUnit**: System.Drawing.Imaging.MetafileFrameUnit, **type**: System.Drawing.Imaging.EmfType)

**Parameters**

- **referenceHdc** (IntPtr)  
- **frameRect** (RectangleF)  
- **frameUnit** (System.Drawing.Imaging.MetafileFrameUnit)  
- **type** (System.Drawing.Imaging.EmfType)  

---

**Metafile**(**stream**: Stream, **referenceHdc**: IntPtr, **frameRect**: RectangleF, **frameUnit**: System.Drawing.Imaging.MetafileFrameUnit)

**Parameters**

- **stream** (Stream)  
- **referenceHdc** (IntPtr)  
- **frameRect** (RectangleF)  
- **frameUnit** (System.Drawing.Imaging.MetafileFrameUnit)  

---

**Metafile**(**stream**: Stream, **referenceHdc**: IntPtr, **p**: object, **pixel**: System.Drawing.Imaging.MetafileFrameUnit)

**Parameters**

- **stream** (Stream)  
- **referenceHdc** (IntPtr)  
- **p** (object)  
- **pixel** (System.Drawing.Imaging.MetafileFrameUnit)  

---

**Metafile**(**referenceHdc**: IntPtr, **frameRect**: RectangleF, **frameUnit**: System.Drawing.Imaging.MetafileFrameUnit, **type**: System.Drawing.Imaging.EmfType, **description**: string)

**Parameters**

- **referenceHdc** (IntPtr)  
- **frameRect** (RectangleF)  
- **frameUnit** (System.Drawing.Imaging.MetafileFrameUnit)  
- **type** (System.Drawing.Imaging.EmfType)  
- **description** (string)  

---

**Metafile**(**stream**: Stream, **referenceHdc**: IntPtr, **frameRect**: RectangleF, **frameUnit**: System.Drawing.Imaging.MetafileFrameUnit, **type**: System.Drawing.Imaging.EmfType, **description**: string)

**Parameters**

- **stream** (Stream)  
- **referenceHdc** (IntPtr)  
- **frameRect** (RectangleF)  
- **frameUnit** (System.Drawing.Imaging.MetafileFrameUnit)  
- **type** (System.Drawing.Imaging.EmfType)  
- **description** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBounds** | RectangleF |  |
| **GetHenhmetafile** | IntPtr |  |
| **GetMetafileHeader** | [MetafileHeader](MetafileHeader.md) |  |

---

### Method Details

#### GetBounds

**GetBounds**(**unit**: GraphicsUnit): RectangleF

**Parameters**

- **unit** (GraphicsUnit)  

**Returns** RectangleF


---

#### GetHenhmetafile

**GetHenhmetafile**(): IntPtr

**Returns** IntPtr


---

#### GetMetafileHeader

**GetMetafileHeader**(): [MetafileHeader](MetafileHeader.md)

**Returns** [MetafileHeader](MetafileHeader.md)


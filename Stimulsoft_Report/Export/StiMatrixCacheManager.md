---
title: "StiMatrixCacheManager Class"
---

## StiMatrixCacheManager Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMatrixCacheManager**([StiMatrix](StiMatrix.md) matrix, int width, int height, int maxPageHeight) |  |

**StiMatrixCacheManager**(**matrix**: [StiMatrix](StiMatrix.md), **width**: int, **height**: int, **maxPageHeight**: int)

**Parameters**

- **matrix** ([StiMatrix](StiMatrix.md))  
- **width** (int)  
- **height** (int)  
- **maxPageHeight** (int)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **GetMatrixLineData** | [StiMatrixLineData](StiMatrixLineData.md) |  |
| **GetMatrixSegment** | [StiMatrixCacheSegment](StiMatrixCacheSegment.md) |  |
| **LoadSegment** | void |  |
| **ReadSegment** | void |  |
| **SaveSegment** | void |  |
| **WriteSegment** | void |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### GetMatrixLineData

**GetMatrixLineData**(**lineNumber**: int): [StiMatrixLineData](StiMatrixLineData.md)

**Parameters**

- **lineNumber** (int)  

**Returns** [StiMatrixLineData](StiMatrixLineData.md)


---

#### GetMatrixSegment

**GetMatrixSegment**(**index**: int): [StiMatrixCacheSegment](StiMatrixCacheSegment.md)

**Parameters**

- **index** (int)  

**Returns** [StiMatrixCacheSegment](StiMatrixCacheSegment.md)


---

#### LoadSegment

**LoadSegment**(**segment**: [StiMatrixCacheSegment](StiMatrixCacheSegment.md)): void

**Parameters**

- **segment** ([StiMatrixCacheSegment](StiMatrixCacheSegment.md))  


---

#### ReadSegment

**ReadSegment**(**stream**: Stream, **segment**: [StiMatrixCacheSegment](StiMatrixCacheSegment.md)): void

**Parameters**

- **stream** (Stream)  
- **segment** ([StiMatrixCacheSegment](StiMatrixCacheSegment.md))  


---

#### SaveSegment

**SaveSegment**(**segment**: [StiMatrixCacheSegment](StiMatrixCacheSegment.md)): void

**Parameters**

- **segment** ([StiMatrixCacheSegment](StiMatrixCacheSegment.md))  


---

#### WriteSegment

**WriteSegment**(**stream**: Stream, **segment**: [StiMatrixCacheSegment](StiMatrixCacheSegment.md)): void

**Parameters**

- **stream** (Stream)  
- **segment** ([StiMatrixCacheSegment](StiMatrixCacheSegment.md))  


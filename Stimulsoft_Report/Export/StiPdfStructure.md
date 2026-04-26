---
title: "StiPdfStructure Class"
---

## StiPdfStructure Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfStructure**() |  |

**StiPdfStructure**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddRef** | void |  |
| **CreateAcroFormObject** | StiPdfAcroFormObjInfo |  |
| **CreateAnnotObject** | StiPdfAnnotObjInfo |  |
| **CreateContentObject** | StiPdfContentObjInfo |  |
| **CreateFontObject** | StiPdfFontObjInfo |  |
| **CreateObject** | StiPdfObjInfo |  |
| **CreateOutlinesObject** | StiPdfOutlinesObjInfo |  |
| **CreatePatternsObject** | StiPdfPatternsObjInfo |  |
| **CreateStructTreeRootObject** | StiPdfStructTreeRootObjInfo |  |
| **CreateXObject** | StiPdfXObjectObjInfo |  |

---

### Method Details

#### AddRef

**AddRef**(**info**: StiPdfObjInfo): void

**Parameters**

- **info** (StiPdfObjInfo)  


---

#### CreateAcroFormObject

**CreateAcroFormObject**(**addRef**: bool): StiPdfAcroFormObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfAcroFormObjInfo


---

#### CreateAnnotObject

**CreateAnnotObject**(**addRef**: bool, **createAP**: bool, **numberAA**: int): StiPdfAnnotObjInfo

**Parameters**

- **addRef** (bool)  
- **createAP** (bool)  
- **numberAA** (int)  

**Returns** StiPdfAnnotObjInfo


---

#### CreateContentObject

**CreateContentObject**(**addRef**: bool): StiPdfContentObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfContentObjInfo


---

#### CreateFontObject

**CreateFontObject**(**addRef**: bool, **useUnicodeMode**: bool, **standardPdfFonts**: bool, **embeddedFonts**: bool, **annotFont**: bool): StiPdfFontObjInfo

**Parameters**

- **addRef** (bool)  
- **useUnicodeMode** (bool)  
- **standardPdfFonts** (bool)  
- **embeddedFonts** (bool)  
- **annotFont** (bool)  

**Returns** StiPdfFontObjInfo


---

#### CreateObject

**CreateObject**(**addRef**: bool): StiPdfObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfObjInfo


---

#### CreateOutlinesObject

**CreateOutlinesObject**(**addRef**: bool): StiPdfOutlinesObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfOutlinesObjInfo


---

#### CreatePatternsObject

**CreatePatternsObject**(**addRef**: bool): StiPdfPatternsObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfPatternsObjInfo


---

#### CreateStructTreeRootObject

**CreateStructTreeRootObject**(**addRef**: bool): StiPdfStructTreeRootObjInfo

**Parameters**

- **addRef** (bool)  

**Returns** StiPdfStructTreeRootObjInfo


---

#### CreateXObject

**CreateXObject**(**addRef**: bool, **haveMask**: bool): StiPdfXObjectObjInfo

**Parameters**

- **addRef** (bool)  
- **haveMask** (bool)  

**Returns** StiPdfXObjectObjInfo


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AcroForm** | StiPdfAcroFormObjInfo |  |
| **ColorSpace** | StiPdfObjInfo |  |
| **DestOutputProfile** | StiPdfObjInfo |  |
| **EmbeddedFilesList** | List<StiPdfContentObjInfo> |  |
| **EmbeddedJS** | StiPdfContentObjInfo |  |
| **Encode** | StiPdfObjInfo |  |
| **ExtGState** | StiPdfObjInfo |  |
| **FontList** | List<StiPdfFontObjInfo> |  |
| **Info** | StiPdfObjInfo |  |
| **LinkList** | List<StiPdfObjInfo> |  |
| **Metadata** | StiPdfObjInfo |  |
| **OptionalContentGroup** | StiPdfObjInfo |  |
| **Outlines** | StiPdfOutlinesObjInfo |  |
| **OutputIntents** | StiPdfObjInfo |  |
| **PageList** | List<StiPdfContentObjInfo> |  |
| **Pages** | StiPdfObjInfo |  |
| **Patterns** | StiPdfPatternsObjInfo |  |
| **Root** | StiPdfObjInfo |  |
| **StructTreeRoot** | StiPdfStructTreeRootObjInfo |  |
| **XObjectList** | List<StiPdfXObjectObjInfo> |  |

---
title: "StiPdfStructure Class"
---

## StiPdfStructure Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public sealed class StiPdfStructure
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPdfStructure()` |  |

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

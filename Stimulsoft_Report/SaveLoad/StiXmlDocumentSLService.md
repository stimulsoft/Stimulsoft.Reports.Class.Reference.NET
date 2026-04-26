---
title: "StiXmlDocumentSLService Class"
---

## StiXmlDocumentSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that allows to save / load documents.

### Inheritance

Inherits from: [StiDocumentSLService](StiDocumentSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a document from the stream. |
| **LoadAsync** | Task | Loads asynchronously a document from the stream. |
| **RegPropertyNames** `static` | void |  |
| **Save** | void | Saves the current document into the stream. |
| **SaveAsync** | Task | Saves asynchronously the current document into the stream. |

---

### Method Details

#### GetAction

**GetAction**(): [StiSLActions](StiSLActions.md)

Returns actions available for the provider.

**Returns** [StiSLActions](StiSLActions.md) — Available actions.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the provider.

**Returns** string — String with filter.


---

#### Load

**Load**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Loads a document from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report in which loading will be done.  
- **stream** (Stream) — Stream to load document.  


---

#### LoadAsync

**LoadAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Loads asynchronously a document from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report in which loading will be done.  
- **stream** (Stream) — Stream to load document.  

**Returns** Task


---

#### RegPropertyNames `static`

**RegPropertyNames**(**sr**: [StiSerializing](../../Stimulsoft_Base/Serializing/StiSerializing.md)): void

**Parameters**

- **sr** ([StiSerializing](../../Stimulsoft_Base/Serializing/StiSerializing.md))  


---

#### Save

**Save**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Saves the current document into the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Rendered report for saving.  
- **stream** (Stream) — Stream to save documents.  


---

#### SaveAsync

**SaveAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Saves asynchronously the current document into the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Rendered report for saving.  
- **stream** (Stream) — Stream to save documents.  

**Returns** Task


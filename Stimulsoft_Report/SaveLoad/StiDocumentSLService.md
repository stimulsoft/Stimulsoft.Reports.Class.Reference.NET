---
title: "StiDocumentSLService Class"
---

## StiDocumentSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

### Inheritance

Inherits from: [StiSLService](StiSLService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MultiplePages** | bool | If the provider handles with multitude of files then true. If does not then false. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void | Loads a document from the stream. |
| **LoadAsync** | Task | Loads asynchronously a document from the stream. |
| **Save** | void | Saves a document in the stream. |
| **SaveAsync** | Task | Saves asynchronously a document in the stream. |

---

### Method Details

#### Load

**Load**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Loads a document from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report in which loading will be done.  
- **stream** (Stream) — Stream to load documents.  


---

#### LoadAsync

**LoadAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Loads asynchronously a document from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report in which loading will be done.  
- **stream** (Stream) — Stream to load documents.  

**Returns** Task


---

#### Save

**Save**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Saves a document in the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Rendered for saving.  
- **stream** (Stream) — Stream to save documents.  


---

#### SaveAsync

**SaveAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Saves asynchronously a document in the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Rendered for saving.  
- **stream** (Stream) — Stream to save documents.  

**Returns** Task


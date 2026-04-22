---
title: "StiXmlDocumentSLService Class"
---

## StiXmlDocumentSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save / load documents.

```csharp
public class StiXmlDocumentSLService
```

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

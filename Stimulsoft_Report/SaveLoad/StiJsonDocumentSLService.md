---
title: "StiJsonDocumentSLService Class"
---

## StiJsonDocumentSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save / load packed documents.

```csharp
public class StiJsonDocumentSLService
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
| **Save** | void | Saves the current document into the stream. |
| **SaveAsync** | Task | Saves asynchronously the current document into the stream. |

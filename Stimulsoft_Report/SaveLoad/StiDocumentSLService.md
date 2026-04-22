---
title: "StiDocumentSLService Class"
---

## StiDocumentSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiDocumentSLService
```

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

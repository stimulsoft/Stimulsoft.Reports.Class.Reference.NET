---
title: "StiXmlDictionarySLService Class"
---

## StiXmlDictionarySLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save / load dictionaries of data.

```csharp
public class StiXmlDictionarySLService
```

### Inheritance

Inherits from: [StiDictionarySLService](StiDictionarySLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a dictionary from the stream. |
| **LoadAsync** | Task | Loads asynchronously a dictionary from the stream. |
| **Merge** | void | Merge a dictionary from the stream. |
| **MergeAsync** | Task | Merge asynchronously a dictionary from the stream. |
| **Save** | void | Saves a dictionary in the stream. |
| **SaveAsync** | Task | Saves asynchronously a dictionary in the stream. |

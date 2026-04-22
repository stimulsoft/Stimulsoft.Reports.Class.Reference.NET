---
title: "StiJsonPageSLService Class"
---

## StiJsonPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save / load pages.

```csharp
public class StiJsonPageSLService
```

### Inheritance

Inherits from: [StiPageSLService](StiPageSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a page from the stream. |
| **LoadAsync** | Task | Asynchronously loads page data from the specified stream into the given page. |
| **Save** | void | Saves a page in the stream. |
| **SaveAsync** | Task | Asynchronously saves the specified page to the provided stream. |

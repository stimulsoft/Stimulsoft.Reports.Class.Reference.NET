---
title: "StiXmlPageSLService Class"
---

## StiXmlPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

Describes the class that allows to save / load pages.

```csharp
public class StiXmlPageSLService
```

### Inheritance

Inherits from: [StiPageSLService](StiPageSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads the page from the stream. |
| **LoadAsync** | Task | Asynchronously loads the specified page from the provided stream. |
| **Save** | void | Saves the page in the stream. |
| **SaveAsync** | Task | Asynchronously saves the specified page to the provided stream. |

---
title: "StiSaveLoadPageEventArgs Class"
---

## StiSaveLoadPageEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

Describes an argument for the event SavePageToCache and LoadPageFromCache.

```csharp
public class StiSaveLoadPageEventArgs
```

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSaveLoadPageEventArgs**(StiPage page, int pageIndex, string cachePath) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CachePath** | string | Gets a path to the file of the page. |
| **Page** | StiPage | Gets the page to save or load. |
| **PageIndex** | int | Gets the index of the page in RenderedPages collection. |

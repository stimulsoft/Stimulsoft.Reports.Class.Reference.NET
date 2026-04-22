---
title: "StiSLService Class"
---

## StiSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiSLService
```

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetDictionaryFilters** `static` | string | Returns a filter for all available services for saving / loading / merging of dictionary of data. |
| **GetDictionarySLServices** `static` | List<[StiDictionarySLService](StiDictionarySLService.md)> | Returns a filter for all available services for saving / loading of a dictioary of data. |
| **GetDocumentFilters** `static` | string | Returns a filter for all available services for saving / loading of a document. |
| **GetDocumentSLServices** `static` | List<[StiDocumentSLService](StiDocumentSLService.md)> | Returns a container of services for all available services for saving / loading of a document. |
| **GetFilter** | string | Returns a filter for the provider. |
| **GetPageFilters** `static` | string | Returns a filter for all available services for saving / loading of a page. |
| **GetPageSLServices** `static` | List<[StiPageSLService](StiPageSLService.md)> | Returns a container of services for all available services for saving / loading of a page. |
| **GetReportFilters** `static` | string | Returns a filter for all available services for saving / loading of a report. |
| **GetReportSLServices** `static` | List<[StiReportSLService](StiReportSLService.md)> | Returns a container of services for all available services for saving / loading of a eport. |
| **InvokeLoading** | void | Raises the Loading event for this object. |
| **InvokeSaving** | void | Raises the Saving event for this object. |
| **OnLoading** *(+1 overloads)* | void |  |
| **OnSaving** *(+1 overloads)* | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Loading** | EventHandler | Event occurs when loading report engine load one element. |
| **Saving** | EventHandler | Event occurs when saving report engine save one element. |

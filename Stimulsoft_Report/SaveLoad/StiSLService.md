---
title: "StiSLService Class"
---

## StiSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

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

---

### Method Details

#### GetAction

**GetAction**(): [StiSLActions](StiSLActions.md)

Returns actions available for the provider.

**Returns** [StiSLActions](StiSLActions.md) — Available actions.


---

#### GetDictionaryFilters `static`

**GetDictionaryFilters**(**action**: [StiSLActions](StiSLActions.md)): string

Returns a filter for all available services for saving / loading / merging of dictionary of data.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** string — Filter.


---

#### GetDictionarySLServices `static`

**GetDictionarySLServices**(**action**: [StiSLActions](StiSLActions.md)): List<[StiDictionarySLService](StiDictionarySLService.md)>

Returns a filter for all available services for saving / loading of a dictioary of data.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** List<[StiDictionarySLService](StiDictionarySLService.md)> — Container of services.


---

#### GetDocumentFilters `static`

**GetDocumentFilters**(**action**: [StiSLActions](StiSLActions.md)): string

Returns a filter for all available services for saving / loading of a document.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** string — Filter.


---

#### GetDocumentSLServices `static`

**GetDocumentSLServices**(**action**: [StiSLActions](StiSLActions.md)): List<[StiDocumentSLService](StiDocumentSLService.md)>

Returns a container of services for all available services for saving / loading of a document.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** List<[StiDocumentSLService](StiDocumentSLService.md)> — Container of services.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the provider.

**Returns** string — String with filter.


---

#### GetPageFilters `static`

**GetPageFilters**(**action**: [StiSLActions](StiSLActions.md)): string

Returns a filter for all available services for saving / loading of a page.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** string — Filter.


---

#### GetPageSLServices `static`

**GetPageSLServices**(**action**: [StiSLActions](StiSLActions.md)): List<[StiPageSLService](StiPageSLService.md)>

Returns a container of services for all available services for saving / loading of a page.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** List<[StiPageSLService](StiPageSLService.md)> — Container of services.


---

#### GetReportFilters `static`

**GetReportFilters**(**action**: [StiSLActions](StiSLActions.md)): string

Returns a filter for all available services for saving / loading of a report.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** string — Filter.


---

#### GetReportSLServices `static`

**GetReportSLServices**(**action**: [StiSLActions](StiSLActions.md)): List<[StiReportSLService](StiReportSLService.md)>

Returns a container of services for all available services for saving / loading of a eport.

**Parameters**

- **action** ([StiSLActions](StiSLActions.md)) — Action required from services.  

**Returns** List<[StiReportSLService](StiReportSLService.md)> — Container of services.


---

#### InvokeLoading

**InvokeLoading**(): void

Raises the Loading event for this object.


---

#### InvokeSaving

**InvokeSaving**(): void

Raises the Saving event for this object.


---

#### OnLoading

**OnLoading**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  

---

**OnLoading**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


---

#### OnSaving

**OnSaving**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  

---

**OnSaving**(**sender**: object, **e**: EventArgs): void

**Parameters**

- **sender** (object)  
- **e** (EventArgs)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Loading** | EventHandler | Event occurs when loading report engine load one element. |
| **Saving** | EventHandler | Event occurs when saving report engine save one element. |

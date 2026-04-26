---
title: "StiXmlDocumentPageSLService Class"
---

## StiXmlDocumentPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that allows to save / load rendered pages.

### Inheritance

Inherits from: [StiDocumentPageSLService](StiDocumentPageSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads the page from the stream. |
| **LoadAsync** | Task | Asynchronously loads the specified page from the provided stream. |
| **Save** | void | Saves the page in the stream. |
| **SaveAsync** | Task | Asynchronously saves the specified report page to the provided stream. |

---

### Method Details

#### GetAction

**GetAction**(): [StiSLActions](StiSLActions.md)

Returns actions available for the provider.

**Returns** [StiSLActions](StiSLActions.md) — Available actions.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the provider.

**Returns** string — String with filter.


---

#### Load

**Load**(**page**: StiPage, **stream**: Stream): void

Loads the page from the stream.

**Parameters**

- **page** (StiPage) — The page in which loading will be done.  
- **stream** (Stream) — The stream to load pages.  


---

#### LoadAsync

**LoadAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously loads the specified page from the provided stream.

**Parameters**

- **page** (StiPage) — The page object to populate with data loaded from the stream.  
- **stream** (Stream) — The stream containing the data to load into the page.  

**Returns** Task — A task that represents the asynchronous load operation.


---

#### Save

**Save**(**page**: StiPage, **stream**: Stream): void

Saves the page in the stream.

**Parameters**

- **page** (StiPage) — The page for saving.  
- **stream** (Stream) — The stream to save the page.  


---

#### SaveAsync

**SaveAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously saves the specified report page to the provided stream.

**Parameters**

- **page** (StiPage) — The report page to save.  
- **stream** (Stream) — The stream to which the page will be saved.  

**Returns** Task — A task that represents the asynchronous save operation.


---
title: "StiJsonPageSLService Class"
---

## StiJsonPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that allows to save / load pages.

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

Loads a page from the stream.

**Parameters**

- **page** (StiPage) — The page in which loading will be done.  
- **stream** (Stream) — Stream to load pages.  


---

#### LoadAsync

**LoadAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously loads page data from the specified stream into the given page.

**Parameters**

- **page** (StiPage) — The page object into which the data will be loaded. Cannot be null.  
- **stream** (Stream) — The stream containing the page data to load. Must be readable and positioned at the start of the data.  

**Returns** Task — A task that represents the asynchronous load operation.


---

#### Save

**Save**(**page**: StiPage, **stream**: Stream): void

Saves a page in the stream.

**Parameters**

- **page** (StiPage) — Page for saving.  
- **stream** (Stream) — Stream to save page.  


---

#### SaveAsync

**SaveAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously saves the specified page to the provided stream.

**Parameters**

- **page** (StiPage) — The page to be saved. Cannot be null.  
- **stream** (Stream) — The stream to which the page will be saved. Must be writable and cannot be null.  

**Returns** Task — A task that represents the asynchronous save operation.


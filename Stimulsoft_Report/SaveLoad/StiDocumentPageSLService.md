---
title: "StiDocumentPageSLService Class"
---

## StiDocumentPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

### Inheritance

Inherits from: [StiSLService](StiSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void | Loads page content from the specified stream into the given page instance. |
| **LoadAsync** | Task | Asynchronously loads page data from the specified stream into the given page. |
| **Save** | void | Saves the specified page to the provided stream. |
| **SaveAsync** | Task | Asynchronously saves the specified page to the provided stream. |

---

### Method Details

#### Load

**Load**(**page**: StiPage, **stream**: Stream): void

Loads page content from the specified stream into the given page instance.

**Parameters**

- **page** (StiPage) — The page object into which the content will be loaded.  
- **stream** (Stream) — The stream containing the page data to load.  


---

#### LoadAsync

**LoadAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously loads page data from the specified stream into the given page.

**Parameters**

- **page** (StiPage) — The page object into which the data will be loaded.  
- **stream** (Stream) — The stream containing the page data to load.  

**Returns** Task — A task that represents the asynchronous load operation.


---

#### Save

**Save**(**page**: StiPage, **stream**: Stream): void

Saves the specified page to the provided stream.

**Parameters**

- **page** (StiPage) — The page to be saved.  
- **stream** (Stream) — The stream to which the page will be saved.  


---

#### SaveAsync

**SaveAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously saves the specified page to the provided stream.

**Parameters**

- **page** (StiPage) — The page to be saved.  
- **stream** (Stream) — The stream to which the page will be saved.  

**Returns** Task — A task that represents the asynchronous save operation.


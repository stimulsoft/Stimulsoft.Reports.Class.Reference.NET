---
title: "StiPageSLService Class"
---

## StiPageSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

### Inheritance

Inherits from: [StiSLService](StiSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void | Loads the page from the stream. |
| **LoadAsync** | Task | Asynchronously loads page data from the specified stream into the given page. |
| **Save** | void | Saves the page in the stream. |
| **SaveAsync** | Task | Asynchronously saves the specified page to the provided stream. |

---

### Method Details

#### Load

**Load**(**page**: StiPage, **stream**: Stream): void

Loads the page from the stream.

**Parameters**

- **page** (StiPage) — The page in which loading will be done.  
- **stream** (Stream) — The stream to load pages.  


---

#### LoadAsync

**LoadAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously loads page data from the specified stream into the given page.

**Parameters**

- **page** (StiPage) — The page object into which the data will be loaded. Cannot be null.  
- **stream** (Stream) — The stream containing the page data to load. Must be readable and positioned at the start of the data. Cannot be null.  

**Returns** Task — A task that represents the asynchronous load operation.


---

#### Save

**Save**(**page**: StiPage, **stream**: Stream): void

Saves the page in the stream.

**Parameters**

- **page** (StiPage) — The page for saving.  
- **stream** (Stream) — The stream to save page.  


---

#### SaveAsync

**SaveAsync**(**page**: StiPage, **stream**: Stream): Task

Asynchronously saves the specified page to the provided stream.

**Parameters**

- **page** (StiPage) — The page to be saved. Cannot be null.  
- **stream** (Stream) — The stream to which the page will be saved. Must be writable and cannot be null.  

**Returns** Task — A task that represents the asynchronous save operation.


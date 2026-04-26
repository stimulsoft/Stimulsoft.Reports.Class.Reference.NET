---
title: "StiDataExceptionProvider Class"
---

## StiDataExceptionProvider Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HideExceptions** `static` | bool | Gets or sets the value, which indicates not to show the exception from engine of the exception. |
| **HideMessages** `static` | bool | Gets or sets a value indicating whether not to show the message from engine of the message. |
| **UiContext** `static` | SynchronizationContext | Optional UI synchronization context captured on the UI thread (assign once at startup if desired). |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Show** `static` | bool |  |

---

### Method Details

#### Show `static`

**Show**(**exception**: Exception, **rethrow**: bool, **owner**: Form): bool

**Parameters**

- **exception** (Exception)  
- **rethrow** (bool)  
- **owner** (Form)  

**Returns** bool


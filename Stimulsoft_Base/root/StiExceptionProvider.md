---
title: "StiExceptionProvider Class"
---

## StiExceptionProvider Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CustomExceptionProvider** `static` | [IStiCustomExceptionProvider](IStiCustomExceptionProvider.md) |  |
| **DisableSendError** `static` | bool |  |
| **HideExceptions** `static` | bool | Gets or sets the value, which indicates not to show the exception from engine of the exception. |
| **HideMessages** `static` | bool | Gets or sets a value indicating whether not to show the message from engine of the message. |
| **ServerUrl** `static` | string |  |

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


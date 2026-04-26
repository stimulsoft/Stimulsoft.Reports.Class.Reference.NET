---
title: "StiLogService Class"
---

## StiLogService Class

**Namespace:** `Stimulsoft.Report`

The service that is responsible for keeping the log in the report system.

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  
Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ClearLogOnStart** | bool |  |
| **TraceEnabled** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Write** `static` *(+3 overloads)* | void | Writes an message into the log. |
| **WriteLogString** | void | Writes an message into the log. |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### Write `static`

**Write**(**type**: Type, **message**: string): void

Writes an message into the log.

**Parameters**

- **type** (Type) — The type to add to a message.  
- **message** (string) — The message which will be added to the log.  

---

**Write**(**type**: Type, **e**: Exception): void

Writes the log message about exeption.

**Parameters**

- **type** (Type) — The type to add to a message.  
- **e** (Exception) — The exeption which will be added to the log.  

---

**Write**(**message**: string): void

Writes an message into the log.

**Parameters**

- **message** (string) — The message which will be added to the log.  

---

**Write**(**exception**: Exception): void

**Parameters**

- **exception** (Exception)  


---

#### WriteLogString

**WriteLogString**(**s**: string): void

Writes an message into the log.

**Parameters**

- **s** (string) — The message which will be added to the log.  


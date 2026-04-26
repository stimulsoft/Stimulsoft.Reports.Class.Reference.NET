---
title: "StiRenderingEvent Class"
---

## StiRenderingEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRenderingEvent**() | Creates a new object of the type StiRenderingEvent. |
| **StiRenderingEvent**(string script) | Creates a new object of the type StiRenderingEvent with specified arguments. |
| **StiRenderingEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiRenderingEvent**()

Creates a new object of the type StiRenderingEvent.

---

**StiRenderingEvent**(**script**: string)

Creates a new object of the type StiRenderingEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiRenderingEvent**(**parent**: StiComponent)

Creates a new object of the type StiEvent with specified arguments.

**Parameters**

- **parent** (StiComponent) — Component which contain this event.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string | Returns the string representation of the event. |

---

### Method Details

#### ToString

**ToString**(): string

Returns the string representation of the event.

**Returns** string


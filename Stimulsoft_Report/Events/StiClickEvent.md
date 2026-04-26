---
title: "StiClickEvent Class"
---

## StiClickEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClickEvent**() | Creates a new object of the type StiClickEvent. |
| **StiClickEvent**(string script) | Creates a new object of the type StiClickEvent with specified arguments. |
| **StiClickEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiClickEvent**()

Creates a new object of the type StiClickEvent.

---

**StiClickEvent**(**script**: string)

Creates a new object of the type StiClickEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiClickEvent**(**parent**: StiComponent)

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


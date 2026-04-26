---
title: "StiGetValueEndEvent Class"
---

## StiGetValueEndEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetValueEndEvent**() | Creates a new object of the type StiGetTitleEvent. |
| **StiGetValueEndEvent**(string script) | Creates a new object of the type StiGetTitleEvent with specified arguments. |
| **StiGetValueEndEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetValueEndEvent**()

Creates a new object of the type StiGetTitleEvent.

---

**StiGetValueEndEvent**(**script**: string)

Creates a new object of the type StiGetTitleEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetValueEndEvent**(**parent**: StiComponent)

Creates a new object of the type StiEvent with specified arguments.

**Parameters**

- **parent** (StiComponent) — Component which contain this event.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEventType** | Type | Return the type of the event. |
| **GetParameters** | [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] | Returns an array of event parameters. |
| **ToString** | string | Returns the string representation of the event. |

---

### Method Details

#### GetEventType

**GetEventType**(): Type

Return the type of the event.

**Returns** Type — Event type.


---

#### GetParameters

**GetParameters**(): [StiParameterInfo](../CodeDom/StiParameterInfo.md)[]

Returns an array of event parameters.

**Returns** [StiParameterInfo](../CodeDom/StiParameterInfo.md)[] — Array of event parameters.


---

#### ToString

**ToString**(): string

Returns the string representation of the event.

**Returns** string


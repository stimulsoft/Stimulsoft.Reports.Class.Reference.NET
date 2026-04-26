---
title: "StiGetTagEvent Class"
---

## StiGetTagEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetTagEvent**() | Creates a new object of the type StiGetTagEvent. |
| **StiGetTagEvent**(string script) | Creates a new object of the type StiGetTagEvent with specified arguments. |
| **StiGetTagEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetTagEvent**()

Creates a new object of the type StiGetTagEvent.

---

**StiGetTagEvent**(**script**: string)

Creates a new object of the type StiGetTagEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetTagEvent**(**parent**: StiComponent)

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


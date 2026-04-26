---
title: "StiMouseMoveEvent Class"
---

## StiMouseMoveEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMouseMoveEvent**() | Creates a new object of the type StiMouseMoveEvent. |
| **StiMouseMoveEvent**(string script) | Creates a new object of the type StiMouseMoveEvent with specified arguments. |
| **StiMouseMoveEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiMouseMoveEvent**()

Creates a new object of the type StiMouseMoveEvent.

---

**StiMouseMoveEvent**(**script**: string)

Creates a new object of the type StiMouseMoveEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiMouseMoveEvent**(**parent**: StiComponent)

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


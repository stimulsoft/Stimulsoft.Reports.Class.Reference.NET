---
title: "StiFillParametersEvent Class"
---

## StiFillParametersEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFillParametersEvent**() | Creates a new object of the type StiFillParametersEvent. |
| **StiFillParametersEvent**(string script) | Creates a new object of the type StiFillParametersEvent with specified arguments. |
| **StiFillParametersEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiFillParametersEvent**()

Creates a new object of the type StiFillParametersEvent.

---

**StiFillParametersEvent**(**script**: string)

Creates a new object of the type StiFillParametersEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiFillParametersEvent**(**parent**: StiComponent)

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


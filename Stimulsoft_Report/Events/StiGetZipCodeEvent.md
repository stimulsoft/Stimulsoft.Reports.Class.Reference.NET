---
title: "StiGetZipCodeEvent Class"
---

## StiGetZipCodeEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetZipCodeEvent**() | Creates a new object of the type StiGetZipCodeEvent. |
| **StiGetZipCodeEvent**(string script) | Creates a new object of the type StiGetZipCodeEvent with specified arguments. |
| **StiGetZipCodeEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetZipCodeEvent**()

Creates a new object of the type StiGetZipCodeEvent.

---

**StiGetZipCodeEvent**(**script**: string)

Creates a new object of the type StiGetZipCodeEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetZipCodeEvent**(**parent**: StiComponent)

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


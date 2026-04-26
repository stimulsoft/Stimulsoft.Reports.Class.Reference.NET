---
title: "StiGetCrossValueEvent Class"
---

## StiGetCrossValueEvent Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetCrossValueEvent**() | Creates a new object of the type StiGetCrossValueEvent. |
| **StiGetCrossValueEvent**(string script) | Creates a new object of the type StiGetCrossValueEvent with specified arguments. |

**StiGetCrossValueEvent**()

Creates a new object of the type StiGetCrossValueEvent.

---

**StiGetCrossValueEvent**(**script**: string)

Creates a new object of the type StiGetCrossValueEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  


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


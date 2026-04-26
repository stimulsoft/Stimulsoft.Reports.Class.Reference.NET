---
title: "StiGetCutPieListEvent Class"
---

## StiGetCutPieListEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetCutPieListEvent**() | Creates a new object of the type StiGetCutPieListEvent. |
| **StiGetCutPieListEvent**(string script) | Creates a new object of the type StiGetCutPieListEvent with specified arguments. |
| **StiGetCutPieListEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetCutPieListEvent**()

Creates a new object of the type StiGetCutPieListEvent.

---

**StiGetCutPieListEvent**(**script**: string)

Creates a new object of the type StiGetCutPieListEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetCutPieListEvent**(**parent**: StiComponent)

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


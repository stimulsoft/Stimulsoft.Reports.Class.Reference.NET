---
title: "StiProcessCellEvent Class"
---

## StiProcessCellEvent Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiProcessCellEvent**() | Creates a new object of the type StiProcessCellEvent. |
| **StiProcessCellEvent**(string script) | Creates a new object of the type StiProcessCellEvent with specified arguments. |

**StiProcessCellEvent**()

Creates a new object of the type StiProcessCellEvent.

---

**StiProcessCellEvent**(**script**: string)

Creates a new object of the type StiProcessCellEvent with specified arguments.

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


---
title: "StiExportingEvent Class"
---

## StiExportingEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiExportingEvent**() | Creates a new object of the type StiExportingEvent. |
| **StiExportingEvent**(string script) | Creates a new object of the type StiExportingEvent with specified arguments. |
| **StiExportingEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiExportingEvent**()

Creates a new object of the type StiExportingEvent.

---

**StiExportingEvent**(**script**: string)

Creates a new object of the type StiExportingEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiExportingEvent**(**parent**: StiComponent)

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


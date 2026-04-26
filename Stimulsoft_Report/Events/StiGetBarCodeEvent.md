---
title: "StiGetBarCodeEvent Class"
---

## StiGetBarCodeEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetBarCodeEvent**() | Creates a new object of the type StiBarCodeEvent. |
| **StiGetBarCodeEvent**(string script) | Creates a new object of the type StiGetBarCodeEvent with specified arguments. |
| **StiGetBarCodeEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetBarCodeEvent**()

Creates a new object of the type StiBarCodeEvent.

---

**StiGetBarCodeEvent**(**script**: string)

Creates a new object of the type StiGetBarCodeEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetBarCodeEvent**(**parent**: StiComponent)

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


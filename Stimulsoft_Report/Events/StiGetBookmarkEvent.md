---
title: "StiGetBookmarkEvent Class"
---

## StiGetBookmarkEvent Class

**Namespace:** `Stimulsoft.Report.Events`

### Inheritance

Inherits from: StiEvent  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetBookmarkEvent**() | Creates a new object of the type StiGetBookmarkEvent. |
| **StiGetBookmarkEvent**(string script) | Creates a new object of the type StiGetBookmarkEvent with specified arguments. |
| **StiGetBookmarkEvent**(StiComponent parent) | Creates a new object of the type StiEvent with specified arguments. |

**StiGetBookmarkEvent**()

Creates a new object of the type StiGetBookmarkEvent.

---

**StiGetBookmarkEvent**(**script**: string)

Creates a new object of the type StiGetBookmarkEvent with specified arguments.

**Parameters**

- **script** (string) — Script of the event.  

---

**StiGetBookmarkEvent**(**parent**: StiComponent)

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


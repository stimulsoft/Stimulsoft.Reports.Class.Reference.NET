---
title: "ErrorEventArgs Class"
---

## ErrorEventArgs Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Provides data for the Error event.

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **ErrorEventArgs**(object currentObject, [ErrorContext](ErrorContext.md) errorContext) | Initializes a new instance of the ErrorEventArgs class. |

**ErrorEventArgs**(**currentObject**: object, **errorContext**: [ErrorContext](ErrorContext.md))

Initializes a new instance of the ErrorEventArgs class.

**Parameters**

- **currentObject** (object) — The current object.  
- **errorContext** ([ErrorContext](ErrorContext.md)) — The error context.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentObject** | object | Gets the current object the error event is being raised against. |
| **ErrorContext** | [ErrorContext](ErrorContext.md) | Gets the error context. |

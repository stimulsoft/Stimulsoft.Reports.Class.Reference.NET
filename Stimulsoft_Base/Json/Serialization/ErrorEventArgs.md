---
title: "ErrorEventArgs Class"
---

## ErrorEventArgs Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Provides data for the Error event.

```csharp
public class ErrorEventArgs
```

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| `ErrorEventArgs(object currentObject, [ErrorContext](ErrorContext.md) errorContext)` | Initializes a new instance of the ErrorEventArgs class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentObject** | object | Gets the current object the error event is being raised against. |
| **ErrorContext** | [ErrorContext](ErrorContext.md) | Gets the error context. |

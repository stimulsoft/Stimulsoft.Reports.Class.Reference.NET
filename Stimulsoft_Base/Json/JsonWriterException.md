---
title: "JsonWriterException Class"
---

## JsonWriterException Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class JsonWriterException
```

### Inheritance

Inherits from: [JsonException](JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonWriterException()` | Initializes a new instance of the JsonWriterException class. |
| `JsonWriterException(string message)` | Initializes a new instance of the JsonWriterException class with a specified error message. |
| `JsonWriterException(string message, Exception innerException)` | Initializes a new instance of the JsonWriterException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| `JsonWriterException(SerializationInfo info, StreamingContext context)` | Initializes a new instance of the JsonWriterException class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Path** | string | Gets the path to the JSON where the error occurred. |

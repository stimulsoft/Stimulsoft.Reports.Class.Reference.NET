---
title: "JsonReaderException Class"
---

## JsonReaderException Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class JsonReaderException
```

### Inheritance

Inherits from: [JsonException](JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonReaderException()` | Initializes a new instance of the JsonReaderException class. |
| `JsonReaderException(string message)` | Initializes a new instance of the JsonReaderException class with a specified error message. |
| `JsonReaderException(string message, Exception innerException)` | Initializes a new instance of the JsonReaderException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| `JsonReaderException(SerializationInfo info, StreamingContext context)` | Initializes a new instance of the JsonReaderException class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LineNumber** | int | Gets the line number indicating where the error occurred. |
| **LinePosition** | int | Gets the line position indicating where the error occurred. |
| **Path** | string | Gets the path to the JSON where the error occurred. |

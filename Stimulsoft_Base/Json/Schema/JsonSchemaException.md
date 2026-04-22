---
title: "JsonSchemaException Class"
---

## JsonSchemaException Class

**Namespace:** `Stimulsoft.Base.Json.Schema`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class JsonSchemaException
```

### Inheritance

Inherits from: [JsonException](../JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSchemaException**() | Initializes a new instance of the JsonSchemaException class. |
| **JsonSchemaException**(string message) | Initializes a new instance of the JsonSchemaException class with a specified error message. |
| **JsonSchemaException**(string message, Exception innerException) | Initializes a new instance of the JsonSchemaException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonSchemaException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonSchemaException class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LineNumber** | int | Gets the line number indicating where the error occurred. |
| **LinePosition** | int | Gets the line position indicating where the error occurred. |
| **Path** | string | Gets the path to the JSON where the error occurred. |

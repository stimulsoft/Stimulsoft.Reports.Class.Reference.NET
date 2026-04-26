---
title: "JsonSchemaException Class"
---

## JsonSchemaException Class

**Namespace:** `Stimulsoft.Base.Json.Schema`

### Inheritance

Inherits from: [JsonException](../JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSchemaException**() | Initializes a new instance of the JsonSchemaException class. |
| **JsonSchemaException**(string message) | Initializes a new instance of the JsonSchemaException class with a specified error message. |
| **JsonSchemaException**(string message, Exception innerException) | Initializes a new instance of the JsonSchemaException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonSchemaException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonSchemaException class. |

**JsonSchemaException**()

Initializes a new instance of the JsonSchemaException class.

---

**JsonSchemaException**(**message**: string)

Initializes a new instance of the JsonSchemaException class with a specified error message.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  

---

**JsonSchemaException**(**message**: string, **innerException**: Exception)

Initializes a new instance of the JsonSchemaException class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  
- **innerException** (Exception) — The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.  

---

**JsonSchemaException**(**info**: SerializationInfo, **context**: StreamingContext)

Initializes a new instance of the JsonSchemaException class.

**Parameters**

- **info** (SerializationInfo) — The SerializationInfo that holds the serialized object data about the exception being thrown.  
- **context** (StreamingContext) — The StreamingContext that contains contextual information about the source or destination.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LineNumber** | int | Gets the line number indicating where the error occurred. |
| **LinePosition** | int | Gets the line position indicating where the error occurred. |
| **Path** | string | Gets the path to the JSON where the error occurred. |

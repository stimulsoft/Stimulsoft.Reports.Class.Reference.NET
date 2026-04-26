---
title: "JsonWriterException Class"
---

## JsonWriterException Class

**Namespace:** `Stimulsoft.Base.Json`

### Inheritance

Inherits from: [JsonException](JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonWriterException**() | Initializes a new instance of the JsonWriterException class. |
| **JsonWriterException**(string message) | Initializes a new instance of the JsonWriterException class with a specified error message. |
| **JsonWriterException**(string message, Exception innerException) | Initializes a new instance of the JsonWriterException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonWriterException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonWriterException class. |

**JsonWriterException**()

Initializes a new instance of the JsonWriterException class.

---

**JsonWriterException**(**message**: string)

Initializes a new instance of the JsonWriterException class with a specified error message.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  

---

**JsonWriterException**(**message**: string, **innerException**: Exception)

Initializes a new instance of the JsonWriterException class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  
- **innerException** (Exception) — The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.  

---

**JsonWriterException**(**info**: SerializationInfo, **context**: StreamingContext)

Initializes a new instance of the JsonWriterException class.

**Parameters**

- **info** (SerializationInfo) — The SerializationInfo that holds the serialized object data about the exception being thrown.  
- **context** (StreamingContext) — The StreamingContext that contains contextual information about the source or destination.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Path** | string | Gets the path to the JSON where the error occurred. |

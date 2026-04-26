---
title: "JsonSerializationException Class"
---

## JsonSerializationException Class

**Namespace:** `Stimulsoft.Base.Json`

### Inheritance

Inherits from: [JsonException](JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSerializationException**() | Initializes a new instance of the JsonSerializationException class. |
| **JsonSerializationException**(string message) | Initializes a new instance of the JsonSerializationException class with a specified error message. |
| **JsonSerializationException**(string message, Exception innerException) | Initializes a new instance of the JsonSerializationException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonSerializationException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonSerializationException class. |

**JsonSerializationException**()

Initializes a new instance of the JsonSerializationException class.

---

**JsonSerializationException**(**message**: string)

Initializes a new instance of the JsonSerializationException class with a specified error message.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  

---

**JsonSerializationException**(**message**: string, **innerException**: Exception)

Initializes a new instance of the JsonSerializationException class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  
- **innerException** (Exception) — The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.  

---

**JsonSerializationException**(**info**: SerializationInfo, **context**: StreamingContext)

Initializes a new instance of the JsonSerializationException class.

**Parameters**

- **info** (SerializationInfo) — The SerializationInfo that holds the serialized object data about the exception being thrown.  
- **context** (StreamingContext) — The StreamingContext that contains contextual information about the source or destination.  


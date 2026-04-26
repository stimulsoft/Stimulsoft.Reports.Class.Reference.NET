---
title: "JsonException Class"
---

## JsonException Class

**Namespace:** `Stimulsoft.Base.Json`

### Inheritance

Inherits from: Exception  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonException**() | Initializes a new instance of the JsonException class. |
| **JsonException**(string message) | Initializes a new instance of the JsonException class with a specified error message. |
| **JsonException**(string message, Exception innerException) | Initializes a new instance of the JsonException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonException class. |

**JsonException**()

Initializes a new instance of the JsonException class.

---

**JsonException**(**message**: string)

Initializes a new instance of the JsonException class with a specified error message.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  

---

**JsonException**(**message**: string, **innerException**: Exception)

Initializes a new instance of the JsonException class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  
- **innerException** (Exception) — The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.  

---

**JsonException**(**info**: SerializationInfo, **context**: StreamingContext)

Initializes a new instance of the JsonException class.

**Parameters**

- **info** (SerializationInfo) — The SerializationInfo that holds the serialized object data about the exception being thrown.  
- **context** (StreamingContext) — The StreamingContext that contains contextual information about the source or destination.  


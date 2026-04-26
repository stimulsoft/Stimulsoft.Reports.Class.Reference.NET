---
title: "JsonReaderException Class"
---

## JsonReaderException Class

**Namespace:** `Stimulsoft.Base.Json`

### Inheritance

Inherits from: [JsonException](JsonException.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonReaderException**() | Initializes a new instance of the JsonReaderException class. |
| **JsonReaderException**(string message) | Initializes a new instance of the JsonReaderException class with a specified error message. |
| **JsonReaderException**(string message, Exception innerException) | Initializes a new instance of the JsonReaderException class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| **JsonReaderException**(SerializationInfo info, StreamingContext context) | Initializes a new instance of the JsonReaderException class. |

**JsonReaderException**()

Initializes a new instance of the JsonReaderException class.

---

**JsonReaderException**(**message**: string)

Initializes a new instance of the JsonReaderException class with a specified error message.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  

---

**JsonReaderException**(**message**: string, **innerException**: Exception)

Initializes a new instance of the JsonReaderException class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters**

- **message** (string) — The error message that explains the reason for the exception.  
- **innerException** (Exception) — The exception that is the cause of the current exception, or a null reference (Nothing in Visual Basic) if no inner exception is specified.  

---

**JsonReaderException**(**info**: SerializationInfo, **context**: StreamingContext)

Initializes a new instance of the JsonReaderException class.

**Parameters**

- **info** (SerializationInfo) — The SerializationInfo that holds the serialized object data about the exception being thrown.  
- **context** (StreamingContext) — The StreamingContext that contains contextual information about the source or destination.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LineNumber** | int | Gets the line number indicating where the error occurred. |
| **LinePosition** | int | Gets the line position indicating where the error occurred. |
| **Path** | string | Gets the path to the JSON where the error occurred. |

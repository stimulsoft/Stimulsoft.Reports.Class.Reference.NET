---
title: "JTokenWriter Class"
---

## JTokenWriter Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

```csharp
public class JTokenWriter
```

### Inheritance

Inherits from: [JsonWriter](../JsonWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JTokenWriter()` | Initializes a new instance of the JTokenWriter class. |
| `JTokenWriter([JContainer](JContainer.md) container)` | Initializes a new instance of the JTokenWriter class writing to the given JContainer. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** | void | Writes the end. |
| **WriteNull** | void | Writes a null value. |
| **WritePropertyName** | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+20 overloads)* | void | Writes a Object value. An error will raised if the value cannot be written as a single JSON token. |

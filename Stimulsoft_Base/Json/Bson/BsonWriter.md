---
title: "BsonWriter Class"
---

## BsonWriter Class

**Namespace:** `Stimulsoft.Base.Json.Bson`  
**Assembly:** `Stimulsoft.Base`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

```csharp
public class BsonWriter
```

### Inheritance

Inherits from: [JsonWriter](../JsonWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `BsonWriter(Stream stream)` | Initializes a new instance of the BsonWriter class. |
| `BsonWriter(BinaryWriter writer)` | Initializes a new instance of the BsonWriter class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** | void | Writes the end. |
| **WriteNull** | void | Writes a null value. |
| **WriteObjectId** | void | Writes a Byte[] value that represents a BSON object id. |
| **WritePropertyName** | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON. |
| **WriteRawValue** | void | Writes raw JSON where a value is expected and updates the writer's state. |
| **WriteRegex** | void | Writes a BSON regex. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+20 overloads)* | void | Writes a Object value. An error will raised if the value cannot be written as a single JSON token. |

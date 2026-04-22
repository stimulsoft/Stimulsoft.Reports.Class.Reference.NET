---
title: "JsonTextWriter Class"
---

## JsonTextWriter Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

```csharp
public class JsonTextWriter
```

### Inheritance

Inherits from: [JsonWriter](JsonWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonTextWriter**(TextWriter textWriter) | Creates an instance of the `JsonWriter` class using the specified TextWriter. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** | void | Writes the specified end token. |
| **WriteIndent** | void | Writes indent characters. |
| **WriteIndentSpace** | void | Writes an indent space. |
| **WriteNull** | void | Writes a null value. |
| **WritePropertyName** *(+1 overloads)* | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+22 overloads)* | void | Writes a Object value. An error will raised if the value cannot be written as a single JSON token. |
| **WriteValueDelimiter** | void | Writes the JSON value delimiter. |
| **WriteWhitespace** | void | Writes out the given white space. |

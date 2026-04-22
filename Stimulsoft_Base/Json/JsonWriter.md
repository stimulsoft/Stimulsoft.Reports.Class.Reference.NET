---
title: "JsonWriter Class"
---

## JsonWriter Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

```csharp
public abstract class JsonWriter
```

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonWriter()` | Creates an instance of the `JsonWriter` class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CloseOutput** | bool | Gets or sets a value indicating whether the underlying stream or TextReader should be closed when the writer is closed. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **SetWriteState** | void | Sets the state of the JsonWriter, |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** *(+1 overloads)* | void | Writes the end of the current JSON object or array. |
| **WriteEndArray** | void | Writes the end of an array. |
| **WriteEndConstructor** | void | Writes the end constructor. |
| **WriteEndObject** | void | Writes the end of a JSON object. |
| **WriteIndent** | void | Writes indent characters. |
| **WriteIndentSpace** | void | Writes an indent space. |
| **WriteNull** | void | Writes a null value. |
| **WritePropertyName** *(+1 overloads)* | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON without changing the writer's state. |
| **WriteRawValue** | void | Writes raw JSON where a value is expected and updates the writer's state. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteToken** *(+3 overloads)* | void | Writes the current JsonReader token and its children. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+37 overloads)* | void | Writes a String value. |
| **WriteValueDelimiter** | void | Writes the JSON value delimiter. |
| **WriteWhitespace** | void | Writes out the given white space. |

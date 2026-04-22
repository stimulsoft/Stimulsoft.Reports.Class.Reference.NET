---
title: "JsonTextReader Class"
---

## JsonTextReader Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Represents a reader that provides fast, non-cached, forward-only access to JSON text data.

```csharp
public class JsonTextReader
```

### Inheritance

Inherits from: [JsonReader](JsonReader.md)  
Implements: [IJsonLineInfo](IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonTextReader(TextReader reader)` | Initializes a new instance of the JsonReader class with the specified TextReader. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Changes the state to closed. |
| **HasLineInfo** | bool | Gets a value indicating whether the class can return line information. |
| **Read** | bool |  |
| **ReadAsBytes** | byte[] | Reads the next JSON token from the stream as a Byte[]. |
| **ReadAsDateTime** | DateTime? | Reads the next JSON token from the stream as a Nullable{DateTime}. |
| **ReadAsDateTimeOffset** | DateTimeOffset? | Reads the next JSON token from the stream as a Nullable{DateTimeOffset}. |
| **ReadAsDecimal** | decimal? | Reads the next JSON token from the stream as a Nullable{Decimal}. |
| **ReadAsInt32** | int? | Reads the next JSON token from the stream as a Nullable{Int32}. |
| **ReadAsString** | string | Reads the next JSON token from the stream as a String. |

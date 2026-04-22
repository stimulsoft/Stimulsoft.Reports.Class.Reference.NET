---
title: "JTokenReader Class"
---

## JTokenReader Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

```csharp
public class JTokenReader
```

### Inheritance

Inherits from: [JsonReader](../JsonReader.md)  
Implements: [IJsonLineInfo](../IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JTokenReader([JToken](JToken.md) token)` | Initializes a new instance of the JTokenReader class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Read** | bool | Reads the next JSON token from the stream. |
| **ReadAsBytes** | byte[] | Reads the next JSON token from the stream as a Byte[]. |
| **ReadAsDateTime** | DateTime? | Reads the next JSON token from the stream as a Nullable{DateTime}. |
| **ReadAsDateTimeOffset** | DateTimeOffset? | Reads the next JSON token from the stream as a Nullable{DateTimeOffset}. |
| **ReadAsDecimal** | decimal? | Reads the next JSON token from the stream as a Nullable{Decimal}. |
| **ReadAsInt32** | int? | Reads the next JSON token from the stream as a Nullable{Int32}. |
| **ReadAsString** | string | Reads the next JSON token from the stream as a String. |

---
title: "JsonValidatingReader Class"
---

## JsonValidatingReader Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class JsonValidatingReader
```

### Inheritance

Inherits from: [JsonReader](JsonReader.md)  
Implements: [IJsonLineInfo](IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonValidatingReader([JsonReader](JsonReader.md) reader)` | Initializes a new instance of the JsonValidatingReader class that validates the content returned from the given JsonReader. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ArrayItemCount** | int |  |
| **CurrentItemWriter** | [JTokenWriter](Linq/JTokenWriter.md) |  |
| **CurrentPropertyName** | string |  |
| **IsUniqueArray** | bool |  |
| **UniqueArrayItems** | IList<[JToken](Linq/JToken.md)> |  |
| **set** | internal |  |

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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ValidationEventHandler** | ValidationEventHandler | Sets an event handler for receiving schema validation errors. |

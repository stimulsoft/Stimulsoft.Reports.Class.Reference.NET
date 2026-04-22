---
title: "BsonReader Class"
---

## BsonReader Class

**Namespace:** `Stimulsoft.Base.Json.Bson`  
**Assembly:** `Stimulsoft.Base`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

```csharp
public class BsonReader
```

### Inheritance

Inherits from: [JsonReader](../JsonReader.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BsonReader**(Stream stream) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(BinaryReader reader) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(Stream stream, bool readRootValueAsArray, DateTimeKind dateTimeKindHandling) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(BinaryReader reader, bool readRootValueAsArray, DateTimeKind dateTimeKindHandling) | Initializes a new instance of the BsonReader class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Changes the State to Closed. |
| **Read** | bool | Reads the next JSON token from the stream. |
| **ReadAsBytes** | byte[] | Reads the next JSON token from the stream as a Byte[]. |
| **ReadAsDateTime** | DateTime? | Reads the next JSON token from the stream as a Nullable{DateTime}. |
| **ReadAsDateTimeOffset** | DateTimeOffset? | Reads the next JSON token from the stream as a Nullable{DateTimeOffset}. |
| **ReadAsDecimal** | decimal? | Reads the next JSON token from the stream as a Nullable{Decimal}. |
| **ReadAsInt32** | int? | Reads the next JSON token from the stream as a Nullable{Int32}. |
| **ReadAsString** | string | Reads the next JSON token from the stream as a String. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Length** | int |  |
| **Position** | int |  |
| **Type** | BsonType |  |

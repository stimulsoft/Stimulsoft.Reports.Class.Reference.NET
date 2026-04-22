---
title: "JsonReader Class"
---

## JsonReader Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

```csharp
public abstract class JsonReader
```

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonReader()` | Initializes a new instance of the JsonReader class with the specified TextReader. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CloseInput** | bool | Gets or sets a value indicating whether the underlying stream or TextReader should be closed when the reader is closed. |
| **SupportMultipleContent** | bool | Gets or sets a value indicating whether multiple pieces of JSON content can be read from a continuous stream without erroring. |
| **set** | internal |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Changes the State to Closed. |
| **Dispose** | void | Releases unmanaged and - optionally - managed resources |
| **Read** | bool | Reads the next JSON token from the stream. |
| **ReadAsBytes** | byte[] | Reads the next JSON token from the stream as a Byte[]. |
| **ReadAsDateTime** | DateTime? | Reads the next JSON token from the stream as a Nullable{DateTime}. |
| **ReadAsDateTimeOffset** | DateTimeOffset? | Reads the next JSON token from the stream as a Nullable{DateTimeOffset}. |
| **ReadAsDecimal** | decimal? | Reads the next JSON token from the stream as a Nullable{Decimal}. |
| **ReadAsInt32** | int? | Reads the next JSON token from the stream as a Nullable{Int32}. |
| **ReadAsString** | string | Reads the next JSON token from the stream as a String. |
| **SetStateBasedOnCurrent** | void | Sets the state based on current token type. |
| **SetToken** *(+1 overloads)* | void | Sets the current token. |
| **Skip** | void | Skips the children of the current token. |

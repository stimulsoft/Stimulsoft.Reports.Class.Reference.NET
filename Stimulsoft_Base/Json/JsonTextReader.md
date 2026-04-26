---
title: "JsonTextReader Class"
---

## JsonTextReader Class

**Namespace:** `Stimulsoft.Base.Json`

Represents a reader that provides fast, non-cached, forward-only access to JSON text data.

### Inheritance

Inherits from: [JsonReader](JsonReader.md)  
Implements: [IJsonLineInfo](IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonTextReader**(TextReader reader) | Initializes a new instance of the JsonReader class with the specified TextReader. |

**JsonTextReader**(**reader**: TextReader)

Initializes a new instance of the JsonReader class with the specified TextReader.

**Parameters**

- **reader** (TextReader) — The `TextReader` containing the XML data to read.  


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

---

### Method Details

#### Close

**Close**(): void

Changes the state to closed.


---

#### HasLineInfo

**HasLineInfo**(): bool

Gets a value indicating whether the class can return line information.

**Returns** bool — `true` if LineNumber and LinePosition can be provided; otherwise, `false`.


---

#### Read

**Read**(): bool

**Returns** bool


---

#### ReadAsBytes

**ReadAsBytes**(): byte[]

Reads the next JSON token from the stream as a Byte[].

**Returns** byte[] — A Byte[] or a null reference if the next JSON token is null. This method will return `null` at the end of an array.


---

#### ReadAsDateTime

**ReadAsDateTime**(): DateTime?

Reads the next JSON token from the stream as a Nullable{DateTime}.

**Returns** DateTime? — A String. This method will return `null` at the end of an array.


---

#### ReadAsDateTimeOffset

**ReadAsDateTimeOffset**(): DateTimeOffset?

Reads the next JSON token from the stream as a Nullable{DateTimeOffset}.

**Returns** DateTimeOffset? — A DateTimeOffset. This method will return `null` at the end of an array.


---

#### ReadAsDecimal

**ReadAsDecimal**(): decimal?

Reads the next JSON token from the stream as a Nullable{Decimal}.

**Returns** decimal? — A Nullable{Decimal}. This method will return `null` at the end of an array.


---

#### ReadAsInt32

**ReadAsInt32**(): int?

Reads the next JSON token from the stream as a Nullable{Int32}.

**Returns** int? — A Nullable{Int32}. This method will return `null` at the end of an array.


---

#### ReadAsString

**ReadAsString**(): string

Reads the next JSON token from the stream as a String.

**Returns** string — A String. This method will return `null` at the end of an array.


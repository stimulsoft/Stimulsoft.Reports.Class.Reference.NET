---
title: "JTokenReader Class"
---

## JTokenReader Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

### Inheritance

Inherits from: [JsonReader](../JsonReader.md)  
Implements: [IJsonLineInfo](../IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JTokenReader**([JToken](JToken.md) token) | Initializes a new instance of the JTokenReader class. |

**JTokenReader**(**token**: [JToken](JToken.md))

Initializes a new instance of the JTokenReader class.

**Parameters**

- **token** ([JToken](JToken.md)) — The token to read from.  


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

---

### Method Details

#### Read

**Read**(): bool

Reads the next JSON token from the stream.

**Returns** bool — true if the next token was read successfully; false if there are no more tokens to read.


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

**Returns** DateTimeOffset? — A Nullable{DateTimeOffset}. This method will return `null` at the end of an array.


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


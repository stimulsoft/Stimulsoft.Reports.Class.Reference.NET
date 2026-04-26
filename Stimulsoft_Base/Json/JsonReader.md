---
title: "JsonReader Class"
---

## JsonReader Class

**Namespace:** `Stimulsoft.Base.Json`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonReader**() | Initializes a new instance of the JsonReader class with the specified TextReader. |

**JsonReader**()

Initializes a new instance of the JsonReader class with the specified TextReader.


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

---

### Method Details

#### Close

**Close**(): void

Changes the State to Closed.


---

#### Dispose

**Dispose**(**disposing**: bool): void

Releases unmanaged and - optionally - managed resources

**Parameters**

- **disposing** (bool) — `true` to release both managed and unmanaged resources; `false` to release only unmanaged resources.  


---

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


---

#### SetStateBasedOnCurrent

**SetStateBasedOnCurrent**(): void

Sets the state based on current token type.


---

#### SetToken

**SetToken**(**newToken**: [JsonToken](JsonToken.md)): void

Sets the current token.

**Parameters**

- **newToken** ([JsonToken](JsonToken.md)) — The new token.  

---

**SetToken**(**newToken**: [JsonToken](JsonToken.md), **value**: object): void

Sets the current token and value.

**Parameters**

- **newToken** ([JsonToken](JsonToken.md)) — The new token.  
- **value** (object) — The value.  


---

#### Skip

**Skip**(): void

Skips the children of the current token.


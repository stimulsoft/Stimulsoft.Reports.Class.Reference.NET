---
title: "BsonReader Class"
---

## BsonReader Class

**Namespace:** `Stimulsoft.Base.Json.Bson`

Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.

### Inheritance

Inherits from: [JsonReader](../JsonReader.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BsonReader**(Stream stream) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(BinaryReader reader) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(Stream stream, bool readRootValueAsArray, DateTimeKind dateTimeKindHandling) | Initializes a new instance of the BsonReader class. |
| **BsonReader**(BinaryReader reader, bool readRootValueAsArray, DateTimeKind dateTimeKindHandling) | Initializes a new instance of the BsonReader class. |

**BsonReader**(**stream**: Stream)

Initializes a new instance of the BsonReader class.

**Parameters**

- **stream** (Stream) — The stream.  

---

**BsonReader**(**reader**: BinaryReader)

Initializes a new instance of the BsonReader class.

**Parameters**

- **reader** (BinaryReader) — The reader.  

---

**BsonReader**(**stream**: Stream, **readRootValueAsArray**: bool, **dateTimeKindHandling**: DateTimeKind)

Initializes a new instance of the BsonReader class.

**Parameters**

- **stream** (Stream) — The stream.  
- **readRootValueAsArray** (bool) — if set to `true` the root object will be read as a JSON array.  
- **dateTimeKindHandling** (DateTimeKind) — The DateTimeKind used when reading DateTime values from BSON.  

---

**BsonReader**(**reader**: BinaryReader, **readRootValueAsArray**: bool, **dateTimeKindHandling**: DateTimeKind)

Initializes a new instance of the BsonReader class.

**Parameters**

- **reader** (BinaryReader) — The reader.  
- **readRootValueAsArray** (bool) — if set to `true` the root object will be read as a JSON array.  
- **dateTimeKindHandling** (DateTimeKind) — The DateTimeKind used when reading DateTime values from BSON.  


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

---

### Method Details

#### Close

**Close**(): void

Changes the State to Closed.


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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Length** | int |  |
| **Position** | int |  |
| **Type** | BsonType |  |

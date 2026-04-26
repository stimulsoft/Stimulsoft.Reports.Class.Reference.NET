---
title: "JsonValidatingReader Class"
---

## JsonValidatingReader Class

**Namespace:** `Stimulsoft.Base.Json`

### Inheritance

Inherits from: [JsonReader](JsonReader.md)  
Implements: [IJsonLineInfo](IJsonLineInfo.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonValidatingReader**([JsonReader](JsonReader.md) reader) | Initializes a new instance of the JsonValidatingReader class that validates the content returned from the given JsonReader. |

**JsonValidatingReader**(**reader**: [JsonReader](JsonReader.md))

Initializes a new instance of the JsonValidatingReader class that validates the content returned from the given JsonReader.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader to read from while validating.  


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

**Returns** byte[] — A Byte[] or a null reference if the next JSON token is null.


---

#### ReadAsDateTime

**ReadAsDateTime**(): DateTime?

Reads the next JSON token from the stream as a Nullable{DateTime}.

**Returns** DateTime? — A String. This method will return `null` at the end of an array.


---

#### ReadAsDateTimeOffset

**ReadAsDateTimeOffset**(): DateTimeOffset?

Reads the next JSON token from the stream as a Nullable{DateTimeOffset}.

**Returns** DateTimeOffset? — A Nullable{DateTimeOffset}.


---

#### ReadAsDecimal

**ReadAsDecimal**(): decimal?

Reads the next JSON token from the stream as a Nullable{Decimal}.

**Returns** decimal? — A Nullable{Decimal}.


---

#### ReadAsInt32

**ReadAsInt32**(): int?

Reads the next JSON token from the stream as a Nullable{Int32}.

**Returns** int? — A Nullable{Int32}.


---

#### ReadAsString

**ReadAsString**(): string

Reads the next JSON token from the stream as a String.

**Returns** string — A String. This method will return `null` at the end of an array.


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ValidationEventHandler** | ValidationEventHandler | Sets an event handler for receiving schema validation errors. |

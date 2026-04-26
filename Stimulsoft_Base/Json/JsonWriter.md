---
title: "JsonWriter Class"
---

## JsonWriter Class

**Namespace:** `Stimulsoft.Base.Json`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonWriter**() | Creates an instance of the `JsonWriter` class. |

**JsonWriter**()

Creates an instance of the `JsonWriter` class.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CloseOutput** | bool | Gets or sets a value indicating whether the underlying stream or TextReader should be closed when the writer is closed. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **SetWriteState** | void | Sets the state of the JsonWriter, |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** *(+1 overloads)* | void | Writes the end of the current JSON object or array. |
| **WriteEndArray** | void | Writes the end of an array. |
| **WriteEndConstructor** | void | Writes the end constructor. |
| **WriteEndObject** | void | Writes the end of a JSON object. |
| **WriteIndent** | void | Writes indent characters. |
| **WriteIndentSpace** | void | Writes an indent space. |
| **WriteNull** | void | Writes a null value. |
| **WritePropertyName** *(+1 overloads)* | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON without changing the writer's state. |
| **WriteRawValue** | void | Writes raw JSON where a value is expected and updates the writer's state. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteToken** *(+3 overloads)* | void | Writes the current JsonReader token and its children. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+37 overloads)* | void | Writes a String value. |
| **WriteValueDelimiter** | void | Writes the JSON value delimiter. |
| **WriteWhitespace** | void | Writes out the given white space. |

---

### Method Details

#### Close

**Close**(): void

Closes this stream and the underlying stream.


---

#### Flush

**Flush**(): void

Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream.


---

#### SetWriteState

**SetWriteState**(**token**: [JsonToken](JsonToken.md), **value**: object): void

Sets the state of the JsonWriter,

**Parameters**

- **token** ([JsonToken](JsonToken.md)) — The JsonToken being written.  
- **value** (object) — The value being written.  


---

#### WriteComment

**WriteComment**(**text**: string): void

Writes out a comment `` containing the specified text.

**Parameters**

- **text** (string) — Text to place inside the comment.  


---

#### WriteEnd

**WriteEnd**(): void

Writes the end of the current JSON object or array.

---

**WriteEnd**(**token**: [JsonToken](JsonToken.md)): void

Writes the specified end token.

**Parameters**

- **token** ([JsonToken](JsonToken.md)) — The end token to write.  


---

#### WriteEndArray

**WriteEndArray**(): void

Writes the end of an array.


---

#### WriteEndConstructor

**WriteEndConstructor**(): void

Writes the end constructor.


---

#### WriteEndObject

**WriteEndObject**(): void

Writes the end of a JSON object.


---

#### WriteIndent

**WriteIndent**(): void

Writes indent characters.


---

#### WriteIndentSpace

**WriteIndentSpace**(): void

Writes an indent space.


---

#### WriteNull

**WriteNull**(): void

Writes a null value.


---

#### WritePropertyName

**WritePropertyName**(**name**: string): void

Writes the property name of a name/value pair on a JSON object.

**Parameters**

- **name** (string) — The name of the property.  

---

**WritePropertyName**(**name**: string, **escape**: bool): void

Writes the property name of a name/value pair on a JSON object.

**Parameters**

- **name** (string) — The name of the property.  
- **escape** (bool) — A flag to indicate whether the text should be escaped when it is written as a JSON property name.  


---

#### WriteRaw

**WriteRaw**(**json**: string): void

Writes raw JSON without changing the writer's state.

**Parameters**

- **json** (string) — The raw JSON to write.  


---

#### WriteRawValue

**WriteRawValue**(**json**: string): void

Writes raw JSON where a value is expected and updates the writer's state.

**Parameters**

- **json** (string) — The raw JSON to write.  


---

#### WriteStartArray

**WriteStartArray**(): void

Writes the beginning of a JSON array.


---

#### WriteStartConstructor

**WriteStartConstructor**(**name**: string): void

Writes the start of a constructor with the given name.

**Parameters**

- **name** (string) — The name of the constructor.  


---

#### WriteStartObject

**WriteStartObject**(): void

Writes the beginning of a JSON object.


---

#### WriteToken

**WriteToken**(**reader**: [JsonReader](JsonReader.md)): void

Writes the current JsonReader token and its children.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader to read the token from.  

---

**WriteToken**(**reader**: [JsonReader](JsonReader.md), **writeChildren**: bool): void

Writes the current JsonReader token.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader to read the token from.  
- **writeChildren** (bool) — A flag indicating whether the current token's children should be written.  

---

**WriteToken**(**token**: [JsonToken](JsonToken.md), **value**: object): void

Writes the JsonToken token and its value.

**Parameters**

- **token** ([JsonToken](JsonToken.md)) — The JsonToken to write.  
- **value** (object) — The value to write. A value is only required for tokens that have an associated value, e.g. the String property name for PropertyName. A null value can be passed to the method for token's that don't have a value, e.g. StartObject.  

---

**WriteToken**(**token**: [JsonToken](JsonToken.md)): void

Writes the JsonToken token.

**Parameters**

- **token** ([JsonToken](JsonToken.md)) — The JsonToken to write.  


---

#### WriteUndefined

**WriteUndefined**(): void

Writes an undefined value.


---

#### WriteValue

**WriteValue**(**value**: string): void

Writes a String value.

**Parameters**

- **value** (string) — The String value to write.  

---

**WriteValue**(**value**: int): void

Writes a Int32 value.

**Parameters**

- **value** (int) — The Int32 value to write.  

---

**WriteValue**(**value**: uint): void

**Parameters**

- **value** (uint)  

---

**WriteValue**(**value**: long): void

Writes a Int64 value.

**Parameters**

- **value** (long) — The Int64 value to write.  

---

**WriteValue**(**value**: ulong): void

**Parameters**

- **value** (ulong)  

---

**WriteValue**(**value**: float): void

Writes a Single value.

**Parameters**

- **value** (float) — The Single value to write.  

---

**WriteValue**(**value**: double): void

Writes a Double value.

**Parameters**

- **value** (double) — The Double value to write.  

---

**WriteValue**(**value**: bool): void

Writes a Boolean value.

**Parameters**

- **value** (bool) — The Boolean value to write.  

---

**WriteValue**(**value**: short): void

Writes a Int16 value.

**Parameters**

- **value** (short) — The Int16 value to write.  

---

**WriteValue**(**value**: ushort): void

**Parameters**

- **value** (ushort)  

---

**WriteValue**(**value**: char): void

Writes a Char value.

**Parameters**

- **value** (char) — The Char value to write.  

---

**WriteValue**(**value**: byte): void

Writes a Byte value.

**Parameters**

- **value** (byte) — The Byte value to write.  

---

**WriteValue**(**value**: sbyte): void

**Parameters**

- **value** (sbyte)  

---

**WriteValue**(**value**: decimal): void

Writes a Decimal value.

**Parameters**

- **value** (decimal) — The Decimal value to write.  

---

**WriteValue**(**value**: DateTime): void

Writes a DateTime value.

**Parameters**

- **value** (DateTime) — The DateTime value to write.  

---

**WriteValue**(**value**: DateTimeOffset): void

Writes a DateTimeOffset value.

**Parameters**

- **value** (DateTimeOffset) — The DateTimeOffset value to write.  

---

**WriteValue**(**value**: Guid): void

Writes a Guid value.

**Parameters**

- **value** (Guid) — The Guid value to write.  

---

**WriteValue**(**value**: TimeSpan): void

Writes a TimeSpan value.

**Parameters**

- **value** (TimeSpan) — The TimeSpan value to write.  

---

**WriteValue**(**value**: int?): void

Writes a Nullable{Int32} value.

**Parameters**

- **value** (int?) — The Nullable{Int32} value to write.  

---

**WriteValue**(**value**: uint?): void

**Parameters**

- **value** (uint?)  

---

**WriteValue**(**value**: long?): void

Writes a Nullable{Int64} value.

**Parameters**

- **value** (long?) — The Nullable{Int64} value to write.  

---

**WriteValue**(**value**: ulong?): void

**Parameters**

- **value** (ulong?)  

---

**WriteValue**(**value**: float?): void

Writes a Nullable{Single} value.

**Parameters**

- **value** (float?) — The Nullable{Single} value to write.  

---

**WriteValue**(**value**: double?): void

Writes a Nullable{Double} value.

**Parameters**

- **value** (double?) — The Nullable{Double} value to write.  

---

**WriteValue**(**value**: bool?): void

Writes a Nullable{Boolean} value.

**Parameters**

- **value** (bool?) — The Nullable{Boolean} value to write.  

---

**WriteValue**(**value**: short?): void

Writes a Nullable{Int16} value.

**Parameters**

- **value** (short?) — The Nullable{Int16} value to write.  

---

**WriteValue**(**value**: ushort?): void

**Parameters**

- **value** (ushort?)  

---

**WriteValue**(**value**: char?): void

Writes a Nullable{Char} value.

**Parameters**

- **value** (char?) — The Nullable{Char} value to write.  

---

**WriteValue**(**value**: byte?): void

Writes a Nullable{Byte} value.

**Parameters**

- **value** (byte?) — The Nullable{Byte} value to write.  

---

**WriteValue**(**value**: sbyte?): void

**Parameters**

- **value** (sbyte?)  

---

**WriteValue**(**value**: decimal?): void

Writes a Nullable{Decimal} value.

**Parameters**

- **value** (decimal?) — The Nullable{Decimal} value to write.  

---

**WriteValue**(**value**: DateTime?): void

Writes a Nullable{DateTime} value.

**Parameters**

- **value** (DateTime?) — The Nullable{DateTime} value to write.  

---

**WriteValue**(**value**: DateTimeOffset?): void

Writes a Nullable{DateTimeOffset} value.

**Parameters**

- **value** (DateTimeOffset?) — The Nullable{DateTimeOffset} value to write.  

---

**WriteValue**(**value**: Guid?): void

Writes a Nullable{Guid} value.

**Parameters**

- **value** (Guid?) — The Nullable{Guid} value to write.  

---

**WriteValue**(**value**: TimeSpan?): void

Writes a Nullable{TimeSpan} value.

**Parameters**

- **value** (TimeSpan?) — The Nullable{TimeSpan} value to write.  

---

**WriteValue**(****: bytevalue): void

Writes a Byte[] value.

**Parameters**

- **** (bytevalue)  

---

**WriteValue**(**value**: Uri): void

Writes a Uri value.

**Parameters**

- **value** (Uri) — The Uri value to write.  

---

**WriteValue**(**value**: object): void

Writes a Object value. An error will raised if the value cannot be written as a single JSON token.

**Parameters**

- **value** (object) — The Object value to write.  


---

#### WriteValueDelimiter

**WriteValueDelimiter**(): void

Writes the JSON value delimiter.


---

#### WriteWhitespace

**WriteWhitespace**(**ws**: string): void

Writes out the given white space.

**Parameters**

- **ws** (string) — The string of white space characters.  


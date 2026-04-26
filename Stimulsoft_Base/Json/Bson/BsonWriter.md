---
title: "BsonWriter Class"
---

## BsonWriter Class

**Namespace:** `Stimulsoft.Base.Json.Bson`

Represents a writer that provides a fast, non-cached, forward-only way of generating JSON data.

### Inheritance

Inherits from: [JsonWriter](../JsonWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BsonWriter**(Stream stream) | Initializes a new instance of the BsonWriter class. |
| **BsonWriter**(BinaryWriter writer) | Initializes a new instance of the BsonWriter class. |

**BsonWriter**(**stream**: Stream)

Initializes a new instance of the BsonWriter class.

**Parameters**

- **stream** (Stream) — The stream.  

---

**BsonWriter**(**writer**: BinaryWriter)

Initializes a new instance of the BsonWriter class.

**Parameters**

- **writer** (BinaryWriter) — The writer.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void | Closes this stream and the underlying stream. |
| **Flush** | void | Flushes whatever is in the buffer to the underlying streams and also flushes the underlying stream. |
| **WriteComment** | void | Writes out a comment `` containing the specified text. |
| **WriteEnd** | void | Writes the end. |
| **WriteNull** | void | Writes a null value. |
| **WriteObjectId** | void | Writes a Byte[] value that represents a BSON object id. |
| **WritePropertyName** | void | Writes the property name of a name/value pair on a JSON object. |
| **WriteRaw** | void | Writes raw JSON. |
| **WriteRawValue** | void | Writes raw JSON where a value is expected and updates the writer's state. |
| **WriteRegex** | void | Writes a BSON regex. |
| **WriteStartArray** | void | Writes the beginning of a JSON array. |
| **WriteStartConstructor** | void | Writes the start of a constructor with the given name. |
| **WriteStartObject** | void | Writes the beginning of a JSON object. |
| **WriteUndefined** | void | Writes an undefined value. |
| **WriteValue** *(+20 overloads)* | void | Writes a Object value. An error will raised if the value cannot be written as a single JSON token. |

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

#### WriteComment

**WriteComment**(**text**: string): void

Writes out a comment `` containing the specified text.

**Parameters**

- **text** (string) — Text to place inside the comment.  


---

#### WriteEnd

**WriteEnd**(**token**: [JsonToken](../JsonToken.md)): void

Writes the end.

**Parameters**

- **token** ([JsonToken](../JsonToken.md)) — The token.  


---

#### WriteNull

**WriteNull**(): void

Writes a null value.


---

#### WriteObjectId

**WriteObjectId**(****: bytevalue): void

Writes a Byte[] value that represents a BSON object id.

**Parameters**

- **** (bytevalue)  


---

#### WritePropertyName

**WritePropertyName**(**name**: string): void

Writes the property name of a name/value pair on a JSON object.

**Parameters**

- **name** (string) — The name of the property.  


---

#### WriteRaw

**WriteRaw**(**json**: string): void

Writes raw JSON.

**Parameters**

- **json** (string) — The raw JSON to write.  


---

#### WriteRawValue

**WriteRawValue**(**json**: string): void

Writes raw JSON where a value is expected and updates the writer's state.

**Parameters**

- **json** (string) — The raw JSON to write.  


---

#### WriteRegex

**WriteRegex**(**pattern**: string, **options**: string): void

Writes a BSON regex.

**Parameters**

- **pattern** (string) — The regex pattern.  
- **options** (string) — The regex options.  


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

#### WriteUndefined

**WriteUndefined**(): void

Writes an undefined value.


---

#### WriteValue

**WriteValue**(**value**: object): void

Writes a Object value. An error will raised if the value cannot be written as a single JSON token.

**Parameters**

- **value** (object) — The Object value to write.  

---

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

**WriteValue**(****: bytevalue): void

Writes a Byte[] value.

**Parameters**

- **** (bytevalue)  

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

**WriteValue**(**value**: Uri): void

Writes a Uri value.

**Parameters**

- **value** (Uri) — The Uri value to write.  


---
title: "JsonSerializer Class"
---

## JsonSerializer Class

**Namespace:** `Stimulsoft.Base.Json`

Serializes and deserializes objects into and from the JSON format. The JsonSerializer enables you to control how objects are encoded into JSON.

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonSerializer**() | Initializes a new instance of the JsonSerializer class. |

**JsonSerializer**()

Initializes a new instance of the JsonSerializer class.


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** `static` *(+1 overloads)* | [JsonSerializer](../Json2/JsonSerializer.md) | Creates a new JsonSerializer instance. The JsonSerializer will not use default settings. |
| **CreateDefault** `static` *(+1 overloads)* | [JsonSerializer](../Json2/JsonSerializer.md) | Creates a new JsonSerializer instance. The JsonSerializer will use default settings. |
| **Deserialize** *(+3 overloads)* | object | Deserializes the JSON structure contained by the specified JsonReader. |
| **Populate** *(+1 overloads)* | void | Populates the JSON values onto the target object. |
| **Serialize** *(+3 overloads)* | void | Serializes the specified Object and writes the JSON structure to a `Stream` using the specified TextWriter. |

---

### Method Details

#### Create `static`

**Create**(): [JsonSerializer](../Json2/JsonSerializer.md)

Creates a new JsonSerializer instance. The JsonSerializer will not use default settings.

**Returns** [JsonSerializer](../Json2/JsonSerializer.md) — A new JsonSerializer instance. The JsonSerializer will not use default settings.

---

**Create**(**settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): [JsonSerializer](../Json2/JsonSerializer.md)

Creates a new JsonSerializer instance using the specified JsonSerializerSettings. The JsonSerializer will not use default settings.

**Parameters**

- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The settings to be applied to the JsonSerializer.  

**Returns** [JsonSerializer](../Json2/JsonSerializer.md) — A new JsonSerializer instance using the specified JsonSerializerSettings. The JsonSerializer will not use default settings.


---

#### CreateDefault `static`

**CreateDefault**(): [JsonSerializer](../Json2/JsonSerializer.md)

Creates a new JsonSerializer instance. The JsonSerializer will use default settings.

**Returns** [JsonSerializer](../Json2/JsonSerializer.md) — A new JsonSerializer instance. The JsonSerializer will use default settings.

---

**CreateDefault**(**settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): [JsonSerializer](../Json2/JsonSerializer.md)

Creates a new JsonSerializer instance using the specified JsonSerializerSettings. The JsonSerializer will use default settings.

**Parameters**

- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The settings to be applied to the JsonSerializer.  

**Returns** [JsonSerializer](../Json2/JsonSerializer.md) — A new JsonSerializer instance using the specified JsonSerializerSettings. The JsonSerializer will use default settings.


---

#### Deserialize

**Deserialize**(**reader**: [JsonReader](JsonReader.md)): object

Deserializes the JSON structure contained by the specified JsonReader.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader that contains the JSON structure to deserialize.  

**Returns** object — The Object being deserialized.

---

**Deserialize**(**reader**: TextReader, **objectType**: Type): object

Deserializes the JSON structure contained by the specified StringReader into an instance of the specified type.

**Parameters**

- **reader** (TextReader) — The TextReader containing the object.  
- **objectType** (Type) — The Type of object being deserialized.  

**Returns** object — The instance of being deserialized.

---

**Deserialize**(**reader**: [JsonReader](JsonReader.md)): T

Deserializes the JSON structure contained by the specified JsonReader into an instance of the specified type.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader containing the object.  

**Returns** T — The instance of being deserialized.

---

**Deserialize**(**reader**: [JsonReader](JsonReader.md), **objectType**: Type): object

Deserializes the JSON structure contained by the specified JsonReader into an instance of the specified type.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader containing the object.  
- **objectType** (Type) — The Type of object being deserialized.  

**Returns** object — The instance of being deserialized.


---

#### Populate

**Populate**(**reader**: TextReader, **target**: object): void

Populates the JSON values onto the target object.

**Parameters**

- **reader** (TextReader) — The TextReader that contains the JSON structure to reader values from.  
- **target** (object) — The target object to populate values onto.  

---

**Populate**(**reader**: [JsonReader](JsonReader.md), **target**: object): void

Populates the JSON values onto the target object.

**Parameters**

- **reader** ([JsonReader](JsonReader.md)) — The JsonReader that contains the JSON structure to reader values from.  
- **target** (object) — The target object to populate values onto.  


---

#### Serialize

**Serialize**(**textWriter**: TextWriter, **value**: object): void

Serializes the specified Object and writes the JSON structure to a `Stream` using the specified TextWriter.

**Parameters**

- **textWriter** (TextWriter) — The TextWriter used to write the JSON structure.  
- **value** (object) — The Object to serialize.  

---

**Serialize**(**jsonWriter**: [JsonWriter](JsonWriter.md), **value**: object, **objectType**: Type): void

Serializes the specified Object and writes the JSON structure to a `Stream` using the specified TextWriter.

**Parameters**

- **jsonWriter** ([JsonWriter](JsonWriter.md)) — The JsonWriter used to write the JSON structure.  
- **value** (object) — The Object to serialize.  
- **objectType** (Type) — The type of the value being serialized. This parameter is used when TypeNameHandling is Auto to write out the type name if the type of the value does not match. Specifing the type is optional.  

---

**Serialize**(**textWriter**: TextWriter, **value**: object, **objectType**: Type): void

Serializes the specified Object and writes the JSON structure to a `Stream` using the specified TextWriter.

**Parameters**

- **textWriter** (TextWriter) — The TextWriter used to write the JSON structure.  
- **value** (object) — The Object to serialize.  
- **objectType** (Type) — The type of the value being serialized. This parameter is used when TypeNameHandling is Auto to write out the type name if the type of the value does not match. Specifing the type is optional.  

---

**Serialize**(**jsonWriter**: [JsonWriter](JsonWriter.md), **value**: object): void

Serializes the specified Object and writes the JSON structure to a `Stream` using the specified JsonWriter.

**Parameters**

- **jsonWriter** ([JsonWriter](JsonWriter.md)) — The JsonWriter used to write the JSON structure.  
- **value** (object) — The Object to serialize.  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Error** | EventHandler<[ErrorEventArgs](Serialization/ErrorEventArgs.md)> | Occurs when the JsonSerializer errors during serialization and deserialization. |

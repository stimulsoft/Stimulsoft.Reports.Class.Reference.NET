---
title: "VersionConverter Class"
---

## VersionConverter Class

**Namespace:** `Stimulsoft.Base.Json.Converters`

Converts a Version to and from a string (e.g. "1.2.3.4").

### Inheritance

Inherits from: [JsonConverter](../JsonConverter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified object type. |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

---

### Method Details

#### CanConvert

**CanConvert**(**objectType**: Type): bool

Determines whether this instance can convert the specified object type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** bool — `true` if this instance can convert the specified object type; otherwise, `false`.


---

#### ReadJson

**ReadJson**(**reader**: [JsonReader](../JsonReader.md), **objectType**: Type, **existingValue**: object, **serializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): object

Reads the JSON representation of the object.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — The JsonReader to read from.  
- **objectType** (Type) — Type of the object.  
- **existingValue** (object) — The existing property value of the JSON that is being converted.  
- **serializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The calling serializer.  

**Returns** object — The object value.


---

#### WriteJson

**WriteJson**(**writer**: [JsonWriter](../JsonWriter.md), **value**: object, **serializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): void

Writes the JSON representation of the object.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — The JsonWriter to write to.  
- **value** (object) — The value.  
- **serializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The calling serializer.  


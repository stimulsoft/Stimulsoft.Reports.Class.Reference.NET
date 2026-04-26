---
title: "IsoDateTimeConverter Class"
---

## IsoDateTimeConverter Class

**Namespace:** `Stimulsoft.Base.Json.Converters`

Converts a DateTime to and from the ISO 8601 date format (e.g. 2008-04-12T12:53Z).

### Inheritance

Inherits from: [DateTimeConverterBase](DateTimeConverterBase.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

---

### Method Details

#### ReadJson

**ReadJson**(**reader**: [JsonReader](../JsonReader.md), **objectType**: Type, **existingValue**: object, **serializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): object

Reads the JSON representation of the object.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — The JsonReader to read from.  
- **objectType** (Type) — Type of the object.  
- **existingValue** (object) — The existing value of object being read.  
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


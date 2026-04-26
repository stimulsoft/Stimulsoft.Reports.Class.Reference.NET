---
title: "JsonConvert Class"
---

## JsonConvert Class

**Namespace:** `Stimulsoft.Base.Json`

Provides methods for converting between common language runtime types and JSON types.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultSettings** `static` | [Func](../../Stimulsoft_Report/root/Func.md)<[JsonSerializerSettings](JsonSerializerSettings.md)> | Gets or sets a function that creates default JsonSerializerSettings. Default settings are automatically used by serialization methods on JsonConvert, and ToObject{T}() and FromObject(object) on JToken. To serialize without using any default settings create a JsonSerializer with Create(). |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DeserializeAnonymousType** `static` *(+1 overloads)* | T | Deserializes the JSON to the given anonymous type. |
| **DeserializeObject** `static` *(+7 overloads)* | object | Deserializes the JSON to a .NET object. |
| **DeserializeObjectAsync** `static` *(+3 overloads)* | Task<T> |  |
| **DeserializeXNode** `static` *(+2 overloads)* | XDocument | Deserializes the XNode from a JSON string. |
| **DeserializeXmlNode** `static` *(+2 overloads)* | XmlDocument | Deserializes the XmlNode from a JSON string. |
| **PopulateObject** `static` *(+1 overloads)* | void | Populates the object with values from the JSON string. |
| **PopulateObjectAsync** `static` | Task |  |
| **SerializeObject** `static` *(+7 overloads)* | string | Serializes the specified object to a JSON string. |
| **SerializeObjectAsync** `static` *(+2 overloads)* | Task<string> |  |
| **SerializeXNode** `static` *(+2 overloads)* | string | Serializes the XNode to a JSON string. |
| **SerializeXmlNode** `static` *(+2 overloads)* | string | Serializes the XML node to a JSON string. |
| **ToString** `static` *(+24 overloads)* | string | Converts the DateTime to its JSON string representation. |

---

### Method Details

#### DeserializeAnonymousType `static`

**DeserializeAnonymousType**(**value**: string, **anonymousTypeObject**: T): T

Deserializes the JSON to the given anonymous type.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **anonymousTypeObject** (T) — The anonymous type object.  

**Returns** T — The deserialized anonymous type from the JSON string.

---

**DeserializeAnonymousType**(**value**: string, **anonymousTypeObject**: T, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): T

Deserializes the JSON to the given anonymous type using JsonSerializerSettings.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **anonymousTypeObject** (T) — The anonymous type object.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to deserialize the object. If this is null, default serialization settings will be used.  

**Returns** T — The deserialized anonymous type from the JSON string.


---

#### DeserializeObject `static`

**DeserializeObject**(**value**: string): object

Deserializes the JSON to a .NET object.

**Parameters**

- **value** (string) — The JSON to deserialize.  

**Returns** object — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): object

Deserializes the JSON to a .NET object using JsonSerializerSettings.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to deserialize the object. If this is null, default serialization settings will be used.  

**Returns** object — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, **type**: Type): object

Deserializes the JSON to the specified .NET type.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **type** (Type) — The Type of object being deserialized.  

**Returns** object — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string): T

Deserializes the JSON to the specified .NET type.

**Parameters**

- **value** (string) — The JSON to deserialize.  

**Returns** T — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, ****: JsonConverterconverters): T

Deserializes the JSON to the specified .NET type using a collection of JsonConverter.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **** (JsonConverterconverters)  

**Returns** T — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): T

Deserializes the JSON to the specified .NET type using JsonSerializerSettings.

**Parameters**

- **value** (string) — The object to deserialize.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to deserialize the object. If this is null, default serialization settings will be used.  

**Returns** T — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, **type**: Type, ****: JsonConverterconverters): object

Deserializes the JSON to the specified .NET type using a collection of JsonConverter.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **type** (Type) — The type of the object to deserialize.  
- **** (JsonConverterconverters)  

**Returns** object — The deserialized object from the JSON string.

---

**DeserializeObject**(**value**: string, **type**: Type, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): object

Deserializes the JSON to the specified .NET type using JsonSerializerSettings.

**Parameters**

- **value** (string) — The JSON to deserialize.  
- **type** (Type) — The type of the object to deserialize to.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to deserialize the object. If this is null, default serialization settings will be used.  

**Returns** object — The deserialized object from the JSON string.


---

#### DeserializeObjectAsync `static`

**DeserializeObjectAsync**(**value**: string): Task<T>

**Parameters**

- **value** (string)  

**Returns** Task<T>

---

**DeserializeObjectAsync**(**value**: string, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): Task<T>

**Parameters**

- **value** (string)  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md))  

**Returns** Task<T>

---

**DeserializeObjectAsync**(**value**: string): Task<object>

**Parameters**

- **value** (string)  

**Returns** Task<object>

---

**DeserializeObjectAsync**(**value**: string, **type**: Type, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): Task<object>

**Parameters**

- **value** (string)  
- **type** (Type)  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md))  

**Returns** Task<object>


---

#### DeserializeXNode `static`

**DeserializeXNode**(**value**: string): XDocument

Deserializes the XNode from a JSON string.

**Parameters**

- **value** (string) — The JSON string.  

**Returns** XDocument — The deserialized XNode

---

**DeserializeXNode**(**value**: string, **deserializeRootElementName**: string): XDocument

Deserializes the XNode from a JSON string nested in a root elment specified by .

**Parameters**

- **value** (string) — The JSON string.  
- **deserializeRootElementName** (string) — The name of the root element to append when deserializing.  

**Returns** XDocument — The deserialized XNode

---

**DeserializeXNode**(**value**: string, **deserializeRootElementName**: string, **writeArrayAttribute**: bool): XDocument

Deserializes the XNode from a JSON string nested in a root elment specified by and writes a .NET array attribute for collections.

**Parameters**

- **value** (string) — The JSON string.  
- **deserializeRootElementName** (string) — The name of the root element to append when deserializing.  
- **writeArrayAttribute** (bool) — A flag to indicate whether to write the Json.NET array attribute. This attribute helps preserve arrays when converting the written XML back to JSON.  

**Returns** XDocument — The deserialized XNode


---

#### DeserializeXmlNode `static`

**DeserializeXmlNode**(**value**: string): XmlDocument

Deserializes the XmlNode from a JSON string.

**Parameters**

- **value** (string) — The JSON string.  

**Returns** XmlDocument — The deserialized XmlNode

---

**DeserializeXmlNode**(**value**: string, **deserializeRootElementName**: string): XmlDocument

Deserializes the XmlNode from a JSON string nested in a root elment specified by .

**Parameters**

- **value** (string) — The JSON string.  
- **deserializeRootElementName** (string) — The name of the root element to append when deserializing.  

**Returns** XmlDocument — The deserialized XmlNode

---

**DeserializeXmlNode**(**value**: string, **deserializeRootElementName**: string, **writeArrayAttribute**: bool): XmlDocument

Deserializes the XmlNode from a JSON string nested in a root elment specified by and writes a .NET array attribute for collections.

**Parameters**

- **value** (string) — The JSON string.  
- **deserializeRootElementName** (string) — The name of the root element to append when deserializing.  
- **writeArrayAttribute** (bool) — A flag to indicate whether to write the Json.NET array attribute. This attribute helps preserve arrays when converting the written XML back to JSON.  

**Returns** XmlDocument — The deserialized XmlNode


---

#### PopulateObject `static`

**PopulateObject**(**value**: string, **target**: object): void

Populates the object with values from the JSON string.

**Parameters**

- **value** (string) — The JSON to populate values from.  
- **target** (object) — The target object to populate values onto.  

---

**PopulateObject**(**value**: string, **target**: object, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): void

Populates the object with values from the JSON string using JsonSerializerSettings.

**Parameters**

- **value** (string) — The JSON to populate values from.  
- **target** (object) — The target object to populate values onto.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to deserialize the object. If this is null, default serialization settings will be used.  


---

#### PopulateObjectAsync `static`

**PopulateObjectAsync**(**value**: string, **target**: object, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): Task

**Parameters**

- **value** (string)  
- **target** (object)  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md))  

**Returns** Task


---

#### SerializeObject `static`

**SerializeObject**(**value**: object): string

Serializes the specified object to a JSON string.

**Parameters**

- **value** (object) — The object to serialize.  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **formatting**: [Formatting](Formatting.md)): string

Serializes the specified object to a JSON string using formatting.

**Parameters**

- **value** (object) — The object to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, ****: JsonConverterconverters): string

Serializes the specified object to a JSON string using a collection of JsonConverter.

**Parameters**

- **value** (object) — The object to serialize.  
- **** (JsonConverterconverters)  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **formatting**: [Formatting](Formatting.md), ****: JsonConverterconverters): string

Serializes the specified object to a JSON string using formatting and a collection of JsonConverter.

**Parameters**

- **value** (object) — The object to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  
- **** (JsonConverterconverters)  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): string

Serializes the specified object to a JSON string using JsonSerializerSettings.

**Parameters**

- **value** (object) — The object to serialize.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to serialize the object. If this is null, default serialization settings will be used.  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **type**: Type, **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): string

Serializes the specified object to a JSON string using a type, formatting and JsonSerializerSettings.

**Parameters**

- **value** (object) — The object to serialize.  
- **type** (Type) — The type of the value being serialized. This parameter is used when TypeNameHandling is Auto to write out the type name if the type of the value does not match. Specifing the type is optional.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to serialize the object. If this is null, default serialization settings will be used.  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **formatting**: [Formatting](Formatting.md), **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): string

Serializes the specified object to a JSON string using formatting and JsonSerializerSettings.

**Parameters**

- **value** (object) — The object to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to serialize the object. If this is null, default serialization settings will be used.  

**Returns** string — A JSON string representation of the object.

---

**SerializeObject**(**value**: object, **type**: Type, **formatting**: [Formatting](Formatting.md), **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): string

Serializes the specified object to a JSON string using a type, formatting and JsonSerializerSettings.

**Parameters**

- **value** (object) — The object to serialize.  
- **type** (Type) — The type of the value being serialized. This parameter is used when TypeNameHandling is Auto to write out the type name if the type of the value does not match. Specifing the type is optional.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md)) — The JsonSerializerSettings used to serialize the object. If this is null, default serialization settings will be used.  

**Returns** string — A JSON string representation of the object.


---

#### SerializeObjectAsync `static`

**SerializeObjectAsync**(**value**: object): Task<string>

**Parameters**

- **value** (object)  

**Returns** Task<string>

---

**SerializeObjectAsync**(**value**: object, **formatting**: [Formatting](Formatting.md)): Task<string>

**Parameters**

- **value** (object)  
- **formatting** ([Formatting](Formatting.md))  

**Returns** Task<string>

---

**SerializeObjectAsync**(**value**: object, **formatting**: [Formatting](Formatting.md), **settings**: [JsonSerializerSettings](JsonSerializerSettings.md)): Task<string>

**Parameters**

- **value** (object)  
- **formatting** ([Formatting](Formatting.md))  
- **settings** ([JsonSerializerSettings](JsonSerializerSettings.md))  

**Returns** Task<string>


---

#### SerializeXNode `static`

**SerializeXNode**(**node**: XObject): string

Serializes the XNode to a JSON string.

**Parameters**

- **node** (XObject) — The node to convert to JSON.  

**Returns** string — A JSON string of the XNode.

---

**SerializeXNode**(**node**: XObject, **formatting**: [Formatting](Formatting.md)): string

Serializes the XNode to a JSON string using formatting.

**Parameters**

- **node** (XObject) — The node to convert to JSON.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  

**Returns** string — A JSON string of the XNode.

---

**SerializeXNode**(**node**: XObject, **formatting**: [Formatting](Formatting.md), **omitRootObject**: bool): string

Serializes the XNode to a JSON string using formatting and omits the root object if is `true`.

**Parameters**

- **node** (XObject) — The node to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  
- **omitRootObject** (bool) — Omits writing the root object.  

**Returns** string — A JSON string of the XNode.


---

#### SerializeXmlNode `static`

**SerializeXmlNode**(**node**: XmlNode): string

Serializes the XML node to a JSON string.

**Parameters**

- **node** (XmlNode) — The node to serialize.  

**Returns** string — A JSON string of the XmlNode.

---

**SerializeXmlNode**(**node**: XmlNode, **formatting**: [Formatting](Formatting.md)): string

Serializes the XML node to a JSON string using formatting.

**Parameters**

- **node** (XmlNode) — The node to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  

**Returns** string — A JSON string of the XmlNode.

---

**SerializeXmlNode**(**node**: XmlNode, **formatting**: [Formatting](Formatting.md), **omitRootObject**: bool): string

Serializes the XML node to a JSON string using formatting and omits the root object if is `true`.

**Parameters**

- **node** (XmlNode) — The node to serialize.  
- **formatting** ([Formatting](Formatting.md)) — Indicates how the output is formatted.  
- **omitRootObject** (bool) — Omits writing the root object.  

**Returns** string — A JSON string of the XmlNode.


---

#### ToString `static`

**ToString**(**value**: DateTime): string

Converts the DateTime to its JSON string representation.

**Parameters**

- **value** (DateTime) — The value to convert.  

**Returns** string — A JSON string representation of the DateTime.

---

**ToString**(**value**: DateTime, **format**: [DateFormatHandling](DateFormatHandling.md), **timeZoneHandling**: [DateTimeZoneHandling](DateTimeZoneHandling.md)): string

Converts the DateTime to its JSON string representation using the DateFormatHandling specified.

**Parameters**

- **value** (DateTime) — The value to convert.  
- **format** ([DateFormatHandling](DateFormatHandling.md)) — The format the date will be converted to.  
- **timeZoneHandling** ([DateTimeZoneHandling](DateTimeZoneHandling.md)) — The time zone handling when the date is converted to a string.  

**Returns** string — A JSON string representation of the DateTime.

---

**ToString**(**value**: DateTimeOffset): string

Converts the DateTimeOffset to its JSON string representation.

**Parameters**

- **value** (DateTimeOffset) — The value to convert.  

**Returns** string — A JSON string representation of the DateTimeOffset.

---

**ToString**(**value**: DateTimeOffset, **format**: [DateFormatHandling](DateFormatHandling.md)): string

Converts the DateTimeOffset to its JSON string representation using the DateFormatHandling specified.

**Parameters**

- **value** (DateTimeOffset) — The value to convert.  
- **format** ([DateFormatHandling](DateFormatHandling.md)) — The format the date will be converted to.  

**Returns** string — A JSON string representation of the DateTimeOffset.

---

**ToString**(**value**: bool): string

Converts the Boolean to its JSON string representation.

**Parameters**

- **value** (bool) — The value to convert.  

**Returns** string — A JSON string representation of the Boolean.

---

**ToString**(**value**: char): string

Converts the Char to its JSON string representation.

**Parameters**

- **value** (char) — The value to convert.  

**Returns** string — A JSON string representation of the Char.

---

**ToString**(**value**: Enum): string

Converts the Enum to its JSON string representation.

**Parameters**

- **value** (Enum) — The value to convert.  

**Returns** string — A JSON string representation of the Enum.

---

**ToString**(**value**: int): string

Converts the Int32 to its JSON string representation.

**Parameters**

- **value** (int) — The value to convert.  

**Returns** string — A JSON string representation of the Int32.

---

**ToString**(**value**: short): string

Converts the Int16 to its JSON string representation.

**Parameters**

- **value** (short) — The value to convert.  

**Returns** string — A JSON string representation of the Int16.

---

**ToString**(**value**: ushort): string

**Parameters**

- **value** (ushort)  

**Returns** string

---

**ToString**(**value**: uint): string

**Parameters**

- **value** (uint)  

**Returns** string

---

**ToString**(**value**: long): string

Converts the Int64 to its JSON string representation.

**Parameters**

- **value** (long) — The value to convert.  

**Returns** string — A JSON string representation of the Int64.

---

**ToString**(**value**: ulong): string

**Parameters**

- **value** (ulong)  

**Returns** string

---

**ToString**(**value**: float): string

Converts the Single to its JSON string representation.

**Parameters**

- **value** (float) — The value to convert.  

**Returns** string — A JSON string representation of the Single.

---

**ToString**(**value**: double): string

Converts the Double to its JSON string representation.

**Parameters**

- **value** (double) — The value to convert.  

**Returns** string — A JSON string representation of the Double.

---

**ToString**(**value**: byte): string

Converts the Byte to its JSON string representation.

**Parameters**

- **value** (byte) — The value to convert.  

**Returns** string — A JSON string representation of the Byte.

---

**ToString**(**value**: sbyte): string

**Parameters**

- **value** (sbyte)  

**Returns** string

---

**ToString**(**value**: decimal): string

Converts the Decimal to its JSON string representation.

**Parameters**

- **value** (decimal) — The value to convert.  

**Returns** string — A JSON string representation of the SByte.

---

**ToString**(**value**: Guid): string

Converts the Guid to its JSON string representation.

**Parameters**

- **value** (Guid) — The value to convert.  

**Returns** string — A JSON string representation of the Guid.

---

**ToString**(**value**: TimeSpan): string

Converts the TimeSpan to its JSON string representation.

**Parameters**

- **value** (TimeSpan) — The value to convert.  

**Returns** string — A JSON string representation of the TimeSpan.

---

**ToString**(**value**: Uri): string

Converts the Uri to its JSON string representation.

**Parameters**

- **value** (Uri) — The value to convert.  

**Returns** string — A JSON string representation of the Uri.

---

**ToString**(**value**: string): string

Converts the String to its JSON string representation.

**Parameters**

- **value** (string) — The value to convert.  

**Returns** string — A JSON string representation of the String.

---

**ToString**(**value**: string, **delimiter**: char): string

Converts the String to its JSON string representation.

**Parameters**

- **value** (string) — The value to convert.  
- **delimiter** (char) — The string delimiter character.  

**Returns** string — A JSON string representation of the String.

---

**ToString**(**value**: string, **delimiter**: char, **stringEscapeHandling**: [StringEscapeHandling](StringEscapeHandling.md)): string

Converts the String to its JSON string representation.

**Parameters**

- **value** (string) — The value to convert.  
- **delimiter** (char) — The string delimiter character.  
- **stringEscapeHandling** ([StringEscapeHandling](StringEscapeHandling.md)) — The string escape handling.  

**Returns** string — A JSON string representation of the String.

---

**ToString**(**value**: object): string

Converts the Object to its JSON string representation.

**Parameters**

- **value** (object) — The value to convert.  

**Returns** string — A JSON string representation of the Object.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **False** | string | Represents JavaScript's boolean value false as a string. This field is read-only. |
| **NaN** | string | Represents JavaScript's NaN as a string. This field is read-only. |
| **NegativeInfinity** | string | Represents JavaScript's negative infinity as a string. This field is read-only. |
| **Null** | string | Represents JavaScript's null as a string. This field is read-only. |
| **PositiveInfinity** | string | Represents JavaScript's positive infinity as a string. This field is read-only. |
| **True** | string | Represents JavaScript's boolean value true as a string. This field is read-only. |
| **Undefined** | string | Represents JavaScript's undefined as a string. This field is read-only. |

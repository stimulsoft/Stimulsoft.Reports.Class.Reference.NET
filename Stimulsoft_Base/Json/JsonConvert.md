---
title: "JsonConvert Class"
---

## JsonConvert Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Provides methods for converting between common language runtime types and JSON types.

```csharp
public static class JsonConvert
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultSettings** `static` | [Func](../../Stimulsoft_Report/Func.md)<[JsonSerializerSettings](JsonSerializerSettings.md)> | Gets or sets a function that creates default JsonSerializerSettings. Default settings are automatically used by serialization methods on JsonConvert, and ToObject{T}() and FromObject(object) on JToken. To serialize without using any default settings create a JsonSerializer with Create(). |

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

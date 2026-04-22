---
title: "XmlNodeConverter Class"
---

## XmlNodeConverter Class

**Namespace:** `Stimulsoft.Base.Json.Converters`  
**Assembly:** `Stimulsoft.Base`

Converts XML to and from JSON.

```csharp
public class XmlNodeConverter
```

### Inheritance

Inherits from: [JsonConverter](../JsonConverter.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DeserializeRootElementName** | string | Gets or sets the name of the root element to insert when deserializing to XML if the JSON structure has produces multiple root elements. |
| **OmitRootObject** | bool | Gets or sets a value indicating whether to write the root JSON object. |
| **WriteArrayAttribute** | bool | Gets or sets a flag to indicate whether to write the Json.NET array attribute. This attribute helps preserve arrays when converting the written XML back to JSON. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified value type. |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

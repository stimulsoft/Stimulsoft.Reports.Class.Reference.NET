---
title: "StringEnumConverter Class"
---

## StringEnumConverter Class

**Namespace:** `Stimulsoft.Base.Json.Converters`  
**Assembly:** `Stimulsoft.Base`

Converts an Enum to and from its name string value.

```csharp
public class StringEnumConverter
```

### Inheritance

Inherits from: [JsonConverter](../JsonConverter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StringEnumConverter()` | Initializes a new instance of the StringEnumConverter class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowIntegerValues** | bool | Gets or sets a value indicating whether integer values are allowed. |
| **CamelCaseText** | bool | Gets or sets a value indicating whether the written enum text should be camel case. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified object type. |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

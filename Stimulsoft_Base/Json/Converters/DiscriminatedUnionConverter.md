---
title: "DiscriminatedUnionConverter Class"
---

## DiscriminatedUnionConverter Class

**Namespace:** `Stimulsoft.Base.Json.Converters`  
**Assembly:** `Stimulsoft.Base`

Converts a F# discriminated union type to and from JSON.

```csharp
public class DiscriminatedUnionConverter
```

### Inheritance

Inherits from: [JsonConverter](../JsonConverter.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **TagReader** | FSharpFunction |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified object type. |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Cases** | List<UnionCase> |  |
| **Constructor** | FSharpFunction |  |
| **FieldReader** | FSharpFunction |  |
| **Fields** | PropertyInfo[] |  |
| **Name** | string |  |
| **Tag** | int |  |

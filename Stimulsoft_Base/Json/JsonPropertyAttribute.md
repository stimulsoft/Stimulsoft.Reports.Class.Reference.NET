---
title: "JsonPropertyAttribute Class"
---

## JsonPropertyAttribute Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class JsonPropertyAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonPropertyAttribute()` | Initializes a new instance of the JsonPropertyAttribute class. |
| `JsonPropertyAttribute(string propertyName)` | Initializes a new instance of the JsonPropertyAttribute class with the specified name. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ItemConverterParameters** | object[] | The parameter list to use when constructing the JsonConverter described by ItemConverterType. If null, the default constructor is used. When non-null, there must be a constructor defined in the JsonConverter that exactly matches the number, order, and type of these parameters. |
| **ItemConverterType** | Type | Gets or sets the converter used when serializing the property's collection items. |
| **PropertyName** | string | Gets or sets the name of the property. |

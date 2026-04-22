---
title: "JsonConverterAttribute Class"
---

## JsonConverterAttribute Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class JsonConverterAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonConverterAttribute**(Type converterType) | Initializes a new instance of the JsonConverterAttribute class. |
| **JsonConverterAttribute**(Type converterType, objectconverterParameters ) | Initializes a new instance of the JsonConverterAttribute class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConverterParameters** | object[] | The parameter list to use when constructing the JsonConverter described by ConverterType. If null, the default constructor is used. |

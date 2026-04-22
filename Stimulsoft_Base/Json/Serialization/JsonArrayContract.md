---
title: "JsonArrayContract Class"
---

## JsonArrayContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Contract details for a Type used by the JsonSerializer.

```csharp
public class JsonArrayContract
```

### Inheritance

Inherits from: [JsonContainerContract](JsonContainerContract.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonArrayContract(Type underlyingType)` | Initializes a new instance of the JsonArrayContract class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CollectionItemType** | Type | Gets the Type of the collection items. |
| **IsMultidimensionalArray** | bool | Gets a value indicating whether the collection type is a multidimensional array. |

---
title: "JsonPropertyCollection Class"
---

## JsonPropertyCollection Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

A collection of JsonProperty objects.

```csharp
public class JsonPropertyCollection
```

### Inheritance

Inherits from: KeyedCollection<string, [JsonProperty](JsonProperty.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonPropertyCollection**(Type type) | Initializes a new instance of the JsonPropertyCollection class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddProperty** | void | Adds a JsonProperty object. |
| **GetClosestMatchProperty** | [JsonProperty](JsonProperty.md) | Gets the closest matching JsonProperty object. First attempts to get an exact case match of propertyName and then a case insensitive match. |
| **GetKeyForItem** | string | When implemented in a derived class, extracts the key from the specified element. |
| **GetProperty** | [JsonProperty](JsonProperty.md) | Gets a property by property name. |

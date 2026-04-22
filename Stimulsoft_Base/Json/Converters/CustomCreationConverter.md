---
title: "CustomCreationConverter<T> Class"
---

## CustomCreationConverter<T> Class

**Namespace:** `Stimulsoft.Base.Json.Converters`  
**Assembly:** `Stimulsoft.Base`

Create a custom object

```csharp
public abstract class CustomCreationConverter<T>
```

### Inheritance

Inherits from: [JsonConverter](../JsonConverter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified object type. |
| **Create** | T | Creates an object which will then be populated by the serializer. |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

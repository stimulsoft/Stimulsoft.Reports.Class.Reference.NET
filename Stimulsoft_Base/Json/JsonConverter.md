---
title: "JsonConverter Class"
---

## JsonConverter Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Converts an object to and from JSON.

```csharp
public abstract class JsonConverter
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanConvert** | bool | Determines whether this instance can convert the specified object type. |
| **GetSchema** | [JsonSchema](Schema/JsonSchema.md) |  |
| **ReadJson** | object | Reads the JSON representation of the object. |
| **WriteJson** | void | Writes the JSON representation of the object. |

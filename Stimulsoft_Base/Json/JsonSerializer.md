---
title: "JsonSerializer Class"
---

## JsonSerializer Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Serializes and deserializes objects into and from the JSON format. The JsonSerializer enables you to control how objects are encoded into JSON.

```csharp
public class JsonSerializer
```

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonSerializer()` | Initializes a new instance of the JsonSerializer class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** `static` *(+1 overloads)* | [JsonSerializer](../Json2/JsonSerializer.md) | Creates a new JsonSerializer instance. The JsonSerializer will not use default settings. |
| **CreateDefault** `static` *(+1 overloads)* | [JsonSerializer](../Json2/JsonSerializer.md) | Creates a new JsonSerializer instance. The JsonSerializer will use default settings. |
| **Deserialize** *(+3 overloads)* | object | Deserializes the JSON structure contained by the specified JsonReader. |
| **Populate** *(+1 overloads)* | void | Populates the JSON values onto the target object. |
| **Serialize** *(+3 overloads)* | void | Serializes the specified Object and writes the JSON structure to a `Stream` using the specified TextWriter. |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **Error** | EventHandler<[ErrorEventArgs](Serialization/ErrorEventArgs.md)> | Occurs when the JsonSerializer errors during serialization and deserialization. |

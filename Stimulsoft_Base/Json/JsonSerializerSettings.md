---
title: "JsonSerializerSettings Class"
---

## JsonSerializerSettings Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies the settings on a JsonSerializer object.

```csharp
public class JsonSerializerSettings
```

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonSerializerSettings()` | Initializes a new instance of the JsonSerializerSettings class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Binder** | [SerializationBinder](SerializationBinder.md) | Gets or sets the SerializationBinder used by the serializer when resolving type names. |
| **ContractResolver** | [IContractResolver](Serialization/IContractResolver.md) | Gets or sets the contract resolver used by the serializer when serializing .NET objects to JSON and vice versa. |
| **Converters** | IList<[JsonConverter](JsonConverter.md)> | Gets or sets a collection JsonConverter that will be used during serialization. |
| **Error** | EventHandler<[ErrorEventArgs](Serialization/ErrorEventArgs.md)> | Gets or sets the error handler called during serialization and deserialization. |
| **ReferenceResolver** | [IReferenceResolver](Serialization/IReferenceResolver.md) | Gets or sets the IReferenceResolver used by the serializer when resolving references. |
| **TraceWriter** | [ITraceWriter](Serialization/ITraceWriter.md) | Gets or sets the ITraceWriter used by the serializer when writing trace messages. |

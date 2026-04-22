---
title: "JsonContract Class"
---

## JsonContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Contract details for a Type used by the JsonSerializer.

```csharp
public abstract class JsonContract
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Converter** | [JsonConverter](../JsonConverter.md) | Gets or sets the default JsonConverter for this contract. |
| **DefaultCreator** | [Func](../../../Stimulsoft_Report/Func.md)<object> | Gets or sets the default creator method used to create the object. |
| **DefaultCreatorNonPublic** | bool | Gets or sets a value indicating whether the default creator is non public. |
| **IsReference** | bool? | Gets or sets whether this type contract is serialized as a reference. |
| **UnderlyingType** | Type | Gets the underlying type for the contract. |

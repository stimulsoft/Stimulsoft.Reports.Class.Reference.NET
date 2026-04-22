---
title: "JsonObjectContract Class"
---

## JsonObjectContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Contract details for a Type used by the JsonSerializer.

```csharp
public class JsonObjectContract
```

### Inheritance

Inherits from: [JsonContainerContract](JsonContainerContract.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `JsonObjectContract(Type underlyingType)` | Initializes a new instance of the JsonObjectContract class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CreatorParameters** | [JsonPropertyCollection](JsonPropertyCollection.md) | Gets a collection of JsonProperty instances that define the parameters used with OverrideCreator. |
| **ExtensionDataGetter** | ExtensionDataGetter | Gets or sets the extension data getter. |
| **ExtensionDataSetter** | ExtensionDataSetter | Gets or sets the extension data setter. |
| **ItemRequired** | Required? | Gets or sets a value that indicates whether the object's properties are required. |
| **MemberSerialization** | [MemberSerialization](../MemberSerialization.md) | Gets or sets the object member serialization. |
| **Properties** | [JsonPropertyCollection](JsonPropertyCollection.md) | Gets the object's properties. |

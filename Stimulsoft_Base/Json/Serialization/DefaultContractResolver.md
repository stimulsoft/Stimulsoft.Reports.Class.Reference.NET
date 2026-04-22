---
title: "DefaultContractResolver Class"
---

## DefaultContractResolver Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Used by JsonSerializer to resolves a JsonContract for a given Type.

```csharp
public class DefaultContractResolver
```

### Inheritance

Implements: [IContractResolver](IContractResolver.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `DefaultContractResolver()` | Initializes a new instance of the DefaultContractResolver class. |
| `DefaultContractResolver(bool shareCache)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DefaultMembersSearchFlags** | BindingFlags |  |
| **IgnoreSerializableAttribute** | bool | Gets or sets a value indicating whether to ignore the SerializableAttribute attribute when serializing and deserializing types. |
| **IgnoreSerializableInterface** | bool | Gets or sets a value indicating whether to ignore the ISerializable interface when serializing and deserializing types. |
| **SerializeCompilerGeneratedMembers** | bool | Gets or sets a value indicating whether compiler generated members should be serialized. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateArrayContract** | [JsonArrayContract](JsonArrayContract.md) | Creates a JsonArrayContract for the given type. |
| **CreateConstructorParameters** | IList<[JsonProperty](JsonProperty.md)> | Creates the constructor parameters. |
| **CreateContract** | [JsonContract](JsonContract.md) | Determines which contract type is created for the given type. |
| **CreateDictionaryContract** | [JsonDictionaryContract](JsonDictionaryContract.md) | Creates a JsonDictionaryContract for the given type. |
| **CreateDynamicContract** | [JsonDynamicContract](JsonDynamicContract.md) | Creates a JsonDynamicContract for the given type. |
| **CreateISerializableContract** | [JsonISerializableContract](JsonISerializableContract.md) | Creates a JsonISerializableContract for the given type. |
| **CreateLinqContract** | [JsonLinqContract](JsonLinqContract.md) | Creates a JsonLinqContract for the given type. |
| **CreateMemberValueProvider** | [IValueProvider](IValueProvider.md) | Creates the IValueProvider used by the serializer to get and set values from a member. |
| **CreateObjectContract** | [JsonObjectContract](JsonObjectContract.md) | Creates a JsonObjectContract for the given type. |
| **CreatePrimitiveContract** | [JsonPrimitiveContract](JsonPrimitiveContract.md) | Creates a JsonPrimitiveContract for the given type. |
| **CreateProperties** | IList<[JsonProperty](JsonProperty.md)> | Creates properties for the given JsonContract. |
| **CreateProperty** | [JsonProperty](JsonProperty.md) | Creates a JsonProperty for the given MemberInfo. |
| **CreatePropertyFromConstructorParameter** | [JsonProperty](JsonProperty.md) | Creates a JsonProperty for the given ParameterInfo. |
| **CreateStringContract** | [JsonStringContract](JsonStringContract.md) | Creates a JsonStringContract for the given type. |
| **Dispose** | void |  |
| **GetResolvedPropertyName** | string | Gets the resolved name of the property. |
| **GetSerializableMembers** | List<MemberInfo> | Gets the serializable members for the type. |
| **MoveNext** | bool |  |
| **Reset** | void |  |
| **ResolveContract** | [JsonContract](JsonContract.md) | Resolves the contract for a given type. |
| **ResolveContractConverter** | [JsonConverter](../JsonConverter.md) | Resolves the default JsonConverter for the contract. |

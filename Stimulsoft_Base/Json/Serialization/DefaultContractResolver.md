---
title: "DefaultContractResolver Class"
---

## DefaultContractResolver Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Used by JsonSerializer to resolves a JsonContract for a given Type.

### Inheritance

Implements: [IContractResolver](IContractResolver.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **DefaultContractResolver**() | Initializes a new instance of the DefaultContractResolver class. |
| **DefaultContractResolver**(bool shareCache) |  |

**DefaultContractResolver**()

Initializes a new instance of the DefaultContractResolver class.

---

**DefaultContractResolver**(**shareCache**: bool)

**Parameters**

- **shareCache** (bool)  


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

---

### Method Details

#### CreateArrayContract

**CreateArrayContract**(**objectType**: Type): [JsonArrayContract](JsonArrayContract.md)

Creates a JsonArrayContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonArrayContract](JsonArrayContract.md) — A JsonArrayContract for the given type.


---

#### CreateConstructorParameters

**CreateConstructorParameters**(**constructor**: ConstructorInfo, **memberProperties**: [JsonPropertyCollection](JsonPropertyCollection.md)): IList<[JsonProperty](JsonProperty.md)>

Creates the constructor parameters.

**Parameters**

- **constructor** (ConstructorInfo) — The constructor to create properties for.  
- **memberProperties** ([JsonPropertyCollection](JsonPropertyCollection.md)) — The type's member properties.  

**Returns** IList<[JsonProperty](JsonProperty.md)> — Properties for the given ConstructorInfo.


---

#### CreateContract

**CreateContract**(**objectType**: Type): [JsonContract](JsonContract.md)

Determines which contract type is created for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonContract](JsonContract.md) — A JsonContract for the given type.


---

#### CreateDictionaryContract

**CreateDictionaryContract**(**objectType**: Type): [JsonDictionaryContract](JsonDictionaryContract.md)

Creates a JsonDictionaryContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonDictionaryContract](JsonDictionaryContract.md) — A JsonDictionaryContract for the given type.


---

#### CreateDynamicContract

**CreateDynamicContract**(**objectType**: Type): [JsonDynamicContract](JsonDynamicContract.md)

Creates a JsonDynamicContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonDynamicContract](JsonDynamicContract.md) — A JsonDynamicContract for the given type.


---

#### CreateISerializableContract

**CreateISerializableContract**(**objectType**: Type): [JsonISerializableContract](JsonISerializableContract.md)

Creates a JsonISerializableContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonISerializableContract](JsonISerializableContract.md) — A JsonISerializableContract for the given type.


---

#### CreateLinqContract

**CreateLinqContract**(**objectType**: Type): [JsonLinqContract](JsonLinqContract.md)

Creates a JsonLinqContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonLinqContract](JsonLinqContract.md) — A JsonLinqContract for the given type.


---

#### CreateMemberValueProvider

**CreateMemberValueProvider**(**member**: MemberInfo): [IValueProvider](IValueProvider.md)

Creates the IValueProvider used by the serializer to get and set values from a member.

**Parameters**

- **member** (MemberInfo) — The member.  

**Returns** [IValueProvider](IValueProvider.md) — The IValueProvider used by the serializer to get and set values from a member.


---

#### CreateObjectContract

**CreateObjectContract**(**objectType**: Type): [JsonObjectContract](JsonObjectContract.md)

Creates a JsonObjectContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonObjectContract](JsonObjectContract.md) — A JsonObjectContract for the given type.


---

#### CreatePrimitiveContract

**CreatePrimitiveContract**(**objectType**: Type): [JsonPrimitiveContract](JsonPrimitiveContract.md)

Creates a JsonPrimitiveContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonPrimitiveContract](JsonPrimitiveContract.md) — A JsonPrimitiveContract for the given type.


---

#### CreateProperties

**CreateProperties**(**type**: Type, **memberSerialization**: [MemberSerialization](../MemberSerialization.md)): IList<[JsonProperty](JsonProperty.md)>

Creates properties for the given JsonContract.

**Parameters**

- **type** (Type) — The type to create properties for.  
- **memberSerialization** ([MemberSerialization](../MemberSerialization.md)) — The member serialization mode for the type.  

**Returns** IList<[JsonProperty](JsonProperty.md)> — Properties for the given JsonContract.


---

#### CreateProperty

**CreateProperty**(**member**: MemberInfo, **memberSerialization**: [MemberSerialization](../MemberSerialization.md)): [JsonProperty](JsonProperty.md)

Creates a JsonProperty for the given MemberInfo.

**Parameters**

- **member** (MemberInfo) — The member to create a JsonProperty for.  
- **memberSerialization** ([MemberSerialization](../MemberSerialization.md)) — The member's parent MemberSerialization.  

**Returns** [JsonProperty](JsonProperty.md) — A created JsonProperty for the given MemberInfo.


---

#### CreatePropertyFromConstructorParameter

**CreatePropertyFromConstructorParameter**(**matchingMemberProperty**: [JsonProperty](JsonProperty.md), **parameterInfo**: ParameterInfo): [JsonProperty](JsonProperty.md)

Creates a JsonProperty for the given ParameterInfo.

**Parameters**

- **matchingMemberProperty** ([JsonProperty](JsonProperty.md)) — The matching member property.  
- **parameterInfo** (ParameterInfo) — The constructor parameter.  

**Returns** [JsonProperty](JsonProperty.md) — A created JsonProperty for the given ParameterInfo.


---

#### CreateStringContract

**CreateStringContract**(**objectType**: Type): [JsonStringContract](JsonStringContract.md)

Creates a JsonStringContract for the given type.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonStringContract](JsonStringContract.md) — A JsonStringContract for the given type.


---

#### Dispose

**Dispose**(): void


---

#### GetResolvedPropertyName

**GetResolvedPropertyName**(**propertyName**: string): string

Gets the resolved name of the property.

**Parameters**

- **propertyName** (string) — Name of the property.  

**Returns** string — Name of the property.


---

#### GetSerializableMembers

**GetSerializableMembers**(**objectType**: Type): List<MemberInfo>

Gets the serializable members for the type.

**Parameters**

- **objectType** (Type) — The type to get serializable members for.  

**Returns** List<MemberInfo> — The serializable members for the type.


---

#### MoveNext

**MoveNext**(): bool

**Returns** bool


---

#### Reset

**Reset**(): void


---

#### ResolveContract

**ResolveContract**(**type**: Type): [JsonContract](JsonContract.md)

Resolves the contract for a given type.

**Parameters**

- **type** (Type) — The type to resolve a contract for.  

**Returns** [JsonContract](JsonContract.md) — The contract for a given type.


---

#### ResolveContractConverter

**ResolveContractConverter**(**objectType**: Type): [JsonConverter](../JsonConverter.md)

Resolves the default JsonConverter for the contract.

**Parameters**

- **objectType** (Type) — Type of the object.  

**Returns** [JsonConverter](../JsonConverter.md) — The contract's default JsonConverter.


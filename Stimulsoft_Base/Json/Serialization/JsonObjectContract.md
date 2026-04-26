---
title: "JsonObjectContract Class"
---

## JsonObjectContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Contract details for a Type used by the JsonSerializer.

### Inheritance

Inherits from: [JsonContainerContract](JsonContainerContract.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonObjectContract**(Type underlyingType) | Initializes a new instance of the JsonObjectContract class. |

**JsonObjectContract**(**underlyingType**: Type)

Initializes a new instance of the JsonObjectContract class.

**Parameters**

- **underlyingType** (Type) — The underlying type for the contract.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CreatorParameters** | [JsonPropertyCollection](JsonPropertyCollection.md) | Gets a collection of JsonProperty instances that define the parameters used with OverrideCreator. |
| **ExtensionDataGetter** | ExtensionDataGetter | Gets or sets the extension data getter. |
| **ExtensionDataSetter** | ExtensionDataSetter | Gets or sets the extension data setter. |
| **ItemRequired** | Required? | Gets or sets a value that indicates whether the object's properties are required. |
| **MemberSerialization** | [MemberSerialization](../MemberSerialization.md) | Gets or sets the object member serialization. |
| **Properties** | [JsonPropertyCollection](JsonPropertyCollection.md) | Gets the object's properties. |

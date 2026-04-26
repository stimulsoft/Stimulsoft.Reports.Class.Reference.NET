---
title: "JsonISerializableContract Class"
---

## JsonISerializableContract Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Contract details for a Type used by the JsonSerializer.

### Inheritance

Inherits from: [JsonContainerContract](JsonContainerContract.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonISerializableContract**(Type underlyingType) | Initializes a new instance of the JsonISerializableContract class. |

**JsonISerializableContract**(**underlyingType**: Type)

Initializes a new instance of the JsonISerializableContract class.

**Parameters**

- **underlyingType** (Type) — The underlying type for the contract.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ISerializableCreator** | ObjectConstructor<object> | Gets or sets the ISerializable object constructor. |

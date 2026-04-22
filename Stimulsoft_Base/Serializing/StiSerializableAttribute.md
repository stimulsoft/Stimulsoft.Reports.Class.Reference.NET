---
title: "StiSerializableAttribute Class"
---

## StiSerializableAttribute Class

**Namespace:** `Stimulsoft.Base.Serializing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiSerializableAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSerializableAttribute()` | Creates a new object of the type StiSerializableAttribute. Visibility is set into the Content. |
| `StiSerializableAttribute([StiSerializationVisibility](StiSerializationVisibility.md) visibility)` | Creates a new object of the type StiSerializableAttribute. |
| `StiSerializableAttribute([StiSerializeTypes](StiSerializeTypes.md) serializeType)` | Creates a new object of the type StiSerializableAttribute. |
| `StiSerializableAttribute([StiSerializationVisibility](StiSerializationVisibility.md) visibility, [StiSerializeTypes](StiSerializeTypes.md) serializeType)` | Creates a new object of the type StiSerializableAttribute. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SerializeType** | [StiSerializeTypes](StiSerializeTypes.md) | Gets or sets serialization type. |
| **Visibility** | [StiSerializationVisibility](StiSerializationVisibility.md) | Gets serialization visibility. |

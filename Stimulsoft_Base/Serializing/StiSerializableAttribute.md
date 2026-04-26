---
title: "StiSerializableAttribute Class"
---

## StiSerializableAttribute Class

**Namespace:** `Stimulsoft.Base.Serializing`

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSerializableAttribute**() | Creates a new object of the type StiSerializableAttribute. Visibility is set into the Content. |
| **StiSerializableAttribute**([StiSerializationVisibility](StiSerializationVisibility.md) visibility) | Creates a new object of the type StiSerializableAttribute. |
| **StiSerializableAttribute**([StiSerializeTypes](StiSerializeTypes.md) serializeType) | Creates a new object of the type StiSerializableAttribute. |
| **StiSerializableAttribute**([StiSerializationVisibility](StiSerializationVisibility.md) visibility, [StiSerializeTypes](StiSerializeTypes.md) serializeType) | Creates a new object of the type StiSerializableAttribute. |

**StiSerializableAttribute**()

Creates a new object of the type StiSerializableAttribute. Visibility is set into the Content.

---

**StiSerializableAttribute**(**visibility**: [StiSerializationVisibility](StiSerializationVisibility.md))

Creates a new object of the type StiSerializableAttribute.

**Parameters**

- **visibility** ([StiSerializationVisibility](StiSerializationVisibility.md)) — Serialized object visibility.  

---

**StiSerializableAttribute**(**serializeType**: [StiSerializeTypes](StiSerializeTypes.md))

Creates a new object of the type StiSerializableAttribute.

**Parameters**

- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md)) — Serializaion type of a serialized object.  

---

**StiSerializableAttribute**(**visibility**: [StiSerializationVisibility](StiSerializationVisibility.md), **serializeType**: [StiSerializeTypes](StiSerializeTypes.md))

Creates a new object of the type StiSerializableAttribute.

**Parameters**

- **visibility** ([StiSerializationVisibility](StiSerializationVisibility.md)) — Serialized object visibility.  
- **serializeType** ([StiSerializeTypes](StiSerializeTypes.md)) — Serializaion type of a serialized object.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SerializeType** | [StiSerializeTypes](StiSerializeTypes.md) | Gets or sets serialization type. |
| **Visibility** | [StiSerializationVisibility](StiSerializationVisibility.md) | Gets serialization visibility. |

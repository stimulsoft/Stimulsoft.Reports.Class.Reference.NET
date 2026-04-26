---
title: "MemberSerialization Enum"
---

## MemberSerialization Enum

**Namespace:** `Stimulsoft.Base.Json`

Specifies the member serialization options for the JsonSerializer.

### Members

| Member | Value | Description |
| --- | --- | --- |
| **OptOut** | 0 | All public members are serialized by default. Members can be excluded using JsonIgnoreAttribute or NonSerializedAttribute. This is the default member serialization mode. |
| **OptIn** | 1 | Only members must be marked with JsonPropertyAttribute or DataMemberAttribute are serialized. This member serialization mode can also be set by marking the class with DataContractAttribute. |
| **Fields** | 2 | All public and private fields are serialized. Members can be excluded using JsonIgnoreAttribute or NonSerializedAttribute. This member serialization mode can also be set by marking the class with SerializableAttribute and setting IgnoreSerializableAttribute on DefaultContractResolver to false. |

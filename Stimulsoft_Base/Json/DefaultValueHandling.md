---
title: "DefaultValueHandling Enum"
---

## DefaultValueHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public enum DefaultValueHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Include** | 0 | Include members where the member value is the same as the member's default value when serializing objects. Included members are written to JSON. Has no effect when deserializing. |
| **Ignore** | 1 | Ignore members where the member value is the same as the member's default value when serializing objects so that is is not written to JSON. This option will ignore all default values (e.g. `null` for objects and nullable types; `0` for integers, decimals and floating point numbers; and `false` for booleans). The default value ignored can be changed by placing the DefaultValueAttribute on the property. |
| **Populate** | 2 | Members with a default value but no JSON will be set to their default value when deserializing. |
| **IgnoreAndPopulate** | Ignore \| Populate | Ignore members where the member value is the same as the member's default value when serializing objects and sets members to their default value when deserializing. |

---
title: "TypeNameHandling Enum"
---

## TypeNameHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public enum TypeNameHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **None** | 0 | Do not include the .NET type name when serializing types. |
| **Objects** | 1 | Include the .NET type name when serializing into a JSON object structure. |
| **Arrays** | 2 | Include the .NET type name when serializing into a JSON array structure. |
| **All** | Objects \| Arrays | Always include the .NET type name when serializing. |
| **Auto** | 4 | Include the .NET type name when the type of the object being serialized is not the same as its declared type. |

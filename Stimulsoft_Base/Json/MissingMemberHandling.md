---
title: "MissingMemberHandling Enum"
---

## MissingMemberHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies missing member handling options for the JsonSerializer.

```csharp
public enum MissingMemberHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Ignore** | 0 | Ignore a missing member and do not attempt to deserialize it. |
| **Error** | 1 | Throw a JsonSerializationException when a missing member is encountered during deserialization. |

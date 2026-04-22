---
title: "ReferenceLoopHandling Enum"
---

## ReferenceLoopHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies reference loop handling options for the JsonSerializer.

```csharp
public enum ReferenceLoopHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Error** | 0 | Throw a JsonSerializationException when a loop is encountered. |
| **Ignore** | 1 | Ignore loop references and do not serialize. |
| **Serialize** | 2 | Serialize loop references. |

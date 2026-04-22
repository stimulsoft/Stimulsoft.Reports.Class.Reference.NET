---
title: "MetadataPropertyHandling Enum"
---

## MetadataPropertyHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies metadata property handling options for the JsonSerializer.

```csharp
public enum MetadataPropertyHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Default** | 0 | Read metadata properties located at the start of a JSON object. |
| **ReadAhead** | 1 | Read metadata properties located anywhere in a JSON object. Note that this setting will impact performance. |
| **Ignore** | 2 | Do not try to read metadata properties. |

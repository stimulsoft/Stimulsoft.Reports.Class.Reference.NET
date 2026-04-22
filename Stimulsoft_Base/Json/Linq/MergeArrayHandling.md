---
title: "MergeArrayHandling Enum"
---

## MergeArrayHandling Enum

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Specifies how JSON arrays are merged together.

```csharp
public enum MergeArrayHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Concat** | 0 | Concatenate arrays. |
| **Union** | 1 | Union arrays, skipping items that already exist. |
| **Replace** | 2 | Replace all array items. |
| **Merge** | 3 | Merge array items together, matched by index. |

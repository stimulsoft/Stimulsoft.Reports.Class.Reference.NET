---
title: "ObjectCreationHandling Enum"
---

## ObjectCreationHandling Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Specifies how object creation is handled by the JsonSerializer.

```csharp
public enum ObjectCreationHandling
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Auto** | 0 | Reuse existing objects, create new objects when needed. |
| **Reuse** | 1 | Only reuse existing objects. |
| **Replace** | 2 | Always create new objects. |

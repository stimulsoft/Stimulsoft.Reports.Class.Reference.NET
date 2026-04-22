---
title: "Required Enum"
---

## Required Enum

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

Indicating whether a property is required.

```csharp
public enum Required
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Default** | 0 | The property is not required. The default state. |
| **AllowNull** | 1 | The property must be defined in JSON but can be a null value. |
| **Always** | 2 | The property must be defined in JSON and cannot be a null value. |

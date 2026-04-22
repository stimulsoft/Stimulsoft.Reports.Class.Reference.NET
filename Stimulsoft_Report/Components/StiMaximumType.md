---
title: "StiMaximumType Enum"
---

## StiMaximumType Enum

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

Types of maximal values in indicator classes.

```csharp
public enum StiMaximumType
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **Auto** |  | Maximal value will be calculated automatically based on values from data list. If calculated maximal value will be less than 0 then 0 will be used as maximum value. |
| **Value** |  | Specified maximal value. |
| **Percent** |  | Maximal value specified as percentage from all maximal values from data list. |
| **Maximum** |  | Maximal value will be calculated automatically based on values from data list. If calculated maximal value will be less than 0 then maximal value will be used as maximum value. |

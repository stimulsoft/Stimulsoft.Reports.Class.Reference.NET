---
title: "StiComponentProgressHelper Class"
---

## StiComponentProgressHelper Class

**Namespace:** `Stimulsoft.Base.Helpers`  
**Assembly:** `Stimulsoft.Base`

```csharp
public static class StiComponentProgressHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CurrentValue** `static` | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** `static` | void |  |
| **Contains** `static` | [StiProgressStatus](StiProgressStatus.md) |  |
| **Dispose** `static` | void |  |
| **FetchAllComponents** `static` | List<[IStiAppComponent](../IStiAppComponent.md)> |  |
| **Init** `static` | void |  |
| **IsActiveProgress** `static` | bool |  |
| **IsHidenProgress** `static` | bool |  |
| **IsLongProgress** `static` | bool |  |
| **Remove** `static` | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **CompletedProgress** | EventHandler |  |
| **Tick** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ProgressDelta** | float |  |
| **TimerInterval** | int |  |

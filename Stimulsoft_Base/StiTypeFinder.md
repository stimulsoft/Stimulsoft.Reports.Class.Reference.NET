---
title: "StiTypeFinder Class"
---

## StiTypeFinder Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

Class contains statistic methods to find types.

```csharp
public sealed class StiTypeFinder
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FindInterface** `static` | bool | Finds in the type exType interface findType. |
| **FindType** `static` | bool | Finds in the type exType the type findType. |
| **GetType** `static` | Type | Returns the type from its string representation. |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **TypeNotFound** | StiTypeNotFoundEventHandler |  |
| **TypeResolve** | EventHandler<[StiTypeEventArgs](StiTypeEventArgs.md)> |  |

---
title: "StiStatesManager Class"
---

## StiStatesManager Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

The class describes the manager of the object state.

```csharp
public sealed class StiStatesManager
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void | Clear all earlier saved object states. |
| **ClearState** | void |  |
| **IsExist** | bool |  |
| **Pop** | object | Gets the object state. |
| **PopBool** | bool | Gets the object state. |
| **PopDecimal** | decimal |  |
| **PopDouble** | double |  |
| **PopFloat** | float |  |
| **PopInt** | int |  |
| **PopInt64** | Int64 |  |
| **PopRange** | [Range](Range.md) |  |
| **Push** | void | Saves the specified object state. |
| **PushBool** | void | Saves the specified object state. |
| **PushDecimal** | void |  |
| **PushDouble** | void |  |
| **PushFloat** | void |  |
| **PushInt** | void |  |
| **PushInt64** | void |  |
| **PushRange** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **From** | object |  |
| **RangeType** | Type |  |
| **To** | object |  |
| **value** | int |  |
| **value** | float |  |
| **value** | double |  |
| **value** | Int64 |  |
| **value** | decimal |  |

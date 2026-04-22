---
title: "StiRecentFileStructure Class"
---

## StiRecentFileStructure Class

**Namespace:** `Stimulsoft.Base.RecentFiles`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiRecentFileStructure
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRecentFileStructure**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Levels** | List<StiRecentFileStructureLevel> |  |
| **RootLevel** | StiRecentFileStructureLevel |  |
| **Sort** | [StiRecentFileStructureSort](StiRecentFileStructureSort.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GotoFolder** | bool |  |
| **MoveBack** | void |  |
| **MoveTo** | bool |  |
| **NewFolder** | bool |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AllowLevelUp** | bool |  |
| **CurrentLevel** | StiRecentFileStructureLevel |  |

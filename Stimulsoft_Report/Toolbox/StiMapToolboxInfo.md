---
title: "StiMapToolboxInfo Class"
---

## StiMapToolboxInfo Class

**Namespace:** `Stimulsoft.Report.Toolbox`  
**Assembly:** `Stimulsoft.Report`

```csharp
public sealed class StiMapToolboxInfo
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMapToolboxInfo([StiMapID](../Maps/StiMapID.md) mapID)` |  |
| `StiMapToolboxInfo([StiMapID](../Maps/StiMapID.md) mapID, stringlocalization )` |  |
| `StiMapToolboxInfo(string customMapID, byteicon )` |  |
| `StiMapToolboxInfo([StiMapCategory](../Maps/StiMapCategory.md) category, string locEnName, string locRuName)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Allow3D** | bool |  |
| **Category** | StiMapCategory? |  |
| **CustomIcon** | byte[] |  |
| **Icon** | string |  |
| **Infos** | List<[StiMapToolboxInfo](StiMapToolboxInfo.md)> |  |
| **Language** | string[] |  |
| **LocEnName** | string |  |
| **LocRuName** | string |  |
| **MapID** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetLangOriginalName** | string |  |
| **ToString** | string |  |

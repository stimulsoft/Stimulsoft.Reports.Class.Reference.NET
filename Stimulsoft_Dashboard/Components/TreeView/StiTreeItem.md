---
title: "StiTreeItem Class"
---

## StiTreeItem Class

**Namespace:** `Stimulsoft.Dashboard.Components.TreeView`  
**Assembly:** `Stimulsoft.Dashboard`

Describes base information about tree-view items.

```csharp
public class StiTreeItem
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreeItem**() |  |
| **StiTreeItem**(object key) |  |
| **StiTreeItem**(object key, [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md) meter) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Items** | List<[StiTreeItem](StiTreeItem.md)> | Nested items of this item. |
| **Key** | object | A unique key of a tree-view item. |
| **Meter** | [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md) | A related meter object. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |

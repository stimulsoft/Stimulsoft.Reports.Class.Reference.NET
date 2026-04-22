---
title: "StiRegionMapAtom Class"
---

## StiRegionMapAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`  
**Assembly:** `Stimulsoft.Dashboard.Drawing`

```csharp
public class StiRegionMapAtom
```

### Inheritance

Inherits from: [StiElementAtom](StiElementAtom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRegionMapAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |
| **StiRegionMapAtom**(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CheckedMapKeys** | List<string> |  |
| **MouseOverMapKey** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetValues** | List<object> |  |
| **Paint** | void |  |
| **Render** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **RegionMapElement** | StiRegionMapElement |  |

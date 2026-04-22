---
title: "StiElementAtom Class"
---

## StiElementAtom Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Atoms`  
**Assembly:** `Stimulsoft.Dashboard.Drawing`

```csharp
public abstract class StiElementAtom
```

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiElementAtom(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable)` |  |
| `StiElementAtom(IStiElement element, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) location, [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable, [StiAnimationEngine](../../Stimulsoft_Report/Painters/Context/Animation/StiAnimationEngine.md) animation)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataTable** | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Element** | IStiElement |  |
| **Location** | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Get** `static` | [StiElementAtom](StiElementAtom.md) |  |
| **Paint** | void |  |
| **PaintElement** `static` | void |  |
| **Render** | void |  |

---
title: "StiTableHelperV2 Class"
---

## StiTableHelperV2 Class

**Namespace:** `Stimulsoft.Report.Design`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiTableHelperV2
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiTableHelperV2([IStiDesignerBase](IStiDesignerBase.md) designer, bool altKeyMode)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SelectedCell** | [IStiTableCell](../Components/Table/IStiTableCell.md) |  |
| **SelectedTable** | StiTable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetDistForResize** `static` | double |  |
| **GetSelectedRectangle** `static` *(+4 overloads)* | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **IsAllowUseInTableMode** `static` | bool |  |
| **ProcessResizeCell** | void |  |
| **ProcessResizeTable** | void |  |
| **ResizeCell** | void |  |
| **ResizeColumns** | bool |  |
| **ResizeRows** | bool |  |
| **RestoreComponentLocation** | void |  |
| **RestoreComponentsLocation** *(+1 overloads)* | void |  |
| **SaveComponentsLocation** | void |  |
| **SaveCursorLocation** | void |  |
| **SaveSelectedRectangle** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IsAnySelected** | bool |  |
| **IsSelectedCell** | bool |  |
| **IsSelectedTable** | bool |  |

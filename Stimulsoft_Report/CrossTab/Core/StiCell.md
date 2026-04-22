---
title: "StiCell Class"
---

## StiCell Class

**Namespace:** `Stimulsoft.Report.CrossTab.Core`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCell
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCell()` |  |
| `StiCell(string text, decimal value, StiCrossField field)` |  |
| `StiCell(string text, decimal value, int width, int height, StiCrossField field)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Field** | StiCrossField |  |
| **FieldCloned** | bool |  |
| **Guid** | string |  |
| **Height** | int |  |
| **HyperlinkValue** | object |  |
| **IsChangeWidthForRightToLeft** | bool |  |
| **IsCrossSummary** | bool |  |
| **IsImage** | bool |  |
| **IsNegativeColor** | bool |  |
| **IsNumeric** | bool |  |
| **KeepMergedCellsTogether** | bool |  |
| **Level** | int |  |
| **ParentCell** | [StiCell](../../Export/StiCell.md) |  |
| **ParentGuid** | string |  |
| **Size** | [SizeD](../../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **SummaryIndex** | int |  |
| **TagValue** | object |  |
| **Text** | string |  |
| **ToolTipValue** | object |  |
| **Value** | object |  |
| **Width** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetComponentPlacement** | string |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CellType** | [StiCellType](../StiCellType.md) |  |
| **TooltipAsHyperlink** | bool |  |

---
title: "StiMatrix Class"
---

## StiMatrix Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMatrix
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiMatrix([StiPagesCollection](../Components/StiPagesCollection.md) pages, [StiExportService](StiExportService.md) service)` |  |
| `StiMatrix([StiPagesCollection](../Components/StiPagesCollection.md) pages, bool checkForExcel, [StiExportService](StiExportService.md) service)` |  |
| `StiMatrix([StiPagesCollection](../Components/StiPagesCollection.md) pages, [StiExportService](StiExportService.md) service, ArrayList styles)` |  |
| `StiMatrix([StiPagesCollection](../Components/StiPagesCollection.md) pages, bool checkForExcel, [StiExportService](StiExportService.md) service, ArrayList styles, [StiDataExportMode](StiDataExportMode.md) dataMode, bool hasDividedPages)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CoordX** | SortedList |  |
| **CoordY** | SortedList |  |
| **HorizontalPageBreaks** | List<int> |  |
| **LinePlacement** | StiTableLineInfo[] |  |
| **ParentBandName** | string[] |  |
| **Styles** | ArrayList |  |
| **TotalWidth** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckStylesNames** | void |  |
| **Clear** | void |  |
| **GetBorderSideIndex** | int |  |
| **GetCellComponent** | StiComponent |  |
| **GetRange** | Rectangle |  |
| **GetRealImageData** | [Image](../../Stimulsoft_Drawing/Image.md) |  |
| **GetStringsFromTag** `static` | string[] |  |
| **GetStyleFromComponent** | [StiCellStyle](StiCellStyle.md) |  |
| **PrepareDocument** | void |  |
| **PrepareTable** | void |  |
| **SetCellComponent** | void |  |
| **SplitTag** `static` | string[] |  |
| **SplitTagWithCache** | string[] |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bookmarks** | [StiMatrixBookmarksCollection](StiMatrixBookmarksCollection.md) |  |
| **BordersX** | [StiMatrixBorderSidesXCollection](StiMatrixBorderSidesXCollection.md) |  |
| **BordersY** | [StiMatrixBorderSidesYCollection](StiMatrixBorderSidesYCollection.md) |  |
| **CellStyles** | [StiMatrixCellStylesCollection](StiMatrixCellStylesCollection.md) |  |
| **Cells** | [StiMatrixCellsCollection](StiMatrixCellsCollection.md) |  |
| **DataArrayLength** | int |  |
| **Fields** | DataField[] |  |
| **Primitive** | [StiRoundedRectanglePrimitive](../Components/StiRoundedRectanglePrimitive.md) |  |
| **Rect** | Rectangle |  |

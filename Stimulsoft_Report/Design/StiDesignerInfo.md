---
title: "StiDesignerInfo Class"
---

## StiDesignerInfo Class

**Namespace:** `Stimulsoft.Report.Design`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDesignerInfo
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDesignerInfo**() | Creates a new object of the type StiDesignerInfo. |
| **StiDesignerInfo**([StiReport](../StiReport.md) report) | Creates a new object of the type StiDesignerInfo. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AlignToGrid** | bool |  |
| **AutoSaveInterval** | int |  |
| **AutoSaveReportToReportClass** | bool |  |
| **CurrentAction** | [StiAction](../../Stimulsoft_Report_Check/StiAction.md) | Currect action in designer. |
| **DefaultSaveFormat** | [StiReportSaveFormatId](../SaveLoad/StiReportSaveFormatId.md) |  |
| **DraggingComponent** | StiComponent |  |
| **DraggingLabelComponent** | StiComponent |  |
| **DrawEventMarkers** | bool |  |
| **DrawMarkersWhenMoving** | bool |  |
| **EnableAutoSaveMode** | bool |  |
| **FillBands** | bool |  |
| **FillComponent** | bool |  |
| **FillContainer** | bool |  |
| **FillCrossBands** | bool |  |
| **ForceDesigningMode** | bool |  |
| **GenerateLocalizedName** | bool |  |
| **GridMode** | [StiGridMode](../StiGridMode.md) |  |
| **GridSizeCentimetres** | double |  |
| **GridSizeHundredthsOfInch** | double |  |
| **GridSizeInch** | double |  |
| **GridSizeMillimeters** | double |  |
| **GridSizePixels** | double |  |
| **GridSizePoints** | double |  |
| **GridSizeScreenPoints** | double |  |
| **IsComponentsMoving** | bool |  |
| **IsTableMode** | bool |  |
| **MarkersStyle** | [StiMarkersStyle](../Components/StiMarkersStyle.md) |  |
| **QuickInfoOverlay** | bool |  |
| **QuickInfoType** | [StiQuickInfoType](../Components/StiQuickInfoType.md) |  |
| **Report** | [StiReport](../StiReport.md) | Gets or sets the report to which these parameters belong. |
| **RunDesignerAfterInsert** | bool |  |
| **ShowDimensionLines** | bool |  |
| **ShowGrid** | bool |  |
| **ShowHeaders** | bool |  |
| **ShowInteractive** | bool |  |
| **ShowOrder** | bool |  |
| **ShowRulers** | bool |  |
| **ShowSmartGuides** | bool |  |
| **UseComponentColor** | bool |  |
| **UseLastFormat** | bool |  |
| **ViewMode** | [StiViewMode](../StiViewMode.md) |  |
| **Zoom** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFillColor** | Color | Gets color of filling. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultGridSizeScreenPoints** | double |  |

---
title: "StiDesignerInfo Class"
---

## StiDesignerInfo Class

**Namespace:** `Stimulsoft.Report.Design`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDesignerInfo**() | Creates a new object of the type StiDesignerInfo. |
| **StiDesignerInfo**([StiReport](../root/StiReport.md) report) | Creates a new object of the type StiDesignerInfo. |

**StiDesignerInfo**()

Creates a new object of the type StiDesignerInfo.

---

**StiDesignerInfo**(**report**: [StiReport](../root/StiReport.md))

Creates a new object of the type StiDesignerInfo.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report are these parameters belong to.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AlignToGrid** | bool |  |
| **AutoSaveInterval** | int |  |
| **AutoSaveReportToReportClass** | bool |  |
| **CurrentAction** | [StiAction](../../Stimulsoft_Report_Check/root/StiAction.md) | Currect action in designer. |
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
| **GridMode** | [StiGridMode](../root/StiGridMode.md) |  |
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
| **Report** | [StiReport](../root/StiReport.md) | Gets or sets the report to which these parameters belong. |
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
| **ViewMode** | [StiViewMode](../root/StiViewMode.md) |  |
| **Zoom** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetFillColor** | Color | Gets color of filling. |

---

### Method Details

#### GetFillColor

**GetFillColor**(**color**: Color): Color

Gets color of filling.

**Parameters**

- **color** (Color) — Component color.  

**Returns** Color — Color of filling.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DefaultGridSizeScreenPoints** | double |  |

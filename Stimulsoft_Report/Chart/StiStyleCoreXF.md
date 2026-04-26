---
title: "StiStyleCoreXF Class"
---

## StiStyleCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BasicStyleColor** | Color |  |
| **Chart** | [IStiChart](IStiChart.md) |  |
| **LegendShowShadow** | bool |  |
| **LocalizedName** | string | Gets a localized name of style. |
| **MarkerVisible** | bool |  |
| **SeriesBorderColor** | Color |  |
| **SeriesBorderThickness** | int |  |
| **SeriesCornerRadius** | StiCornerRadius |  |
| **SeriesShowBorder** | bool |  |
| **SeriesShowShadow** | bool |  |
| **StyleColors** | Color[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillColumn** | void |  |
| **GetAreaBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **GetColorByIndex** | Color |  |
| **GetColorBySeries** | Color |  |
| **GetColors** | Color[] |  |
| **GetColumnBorder** | Color |  |
| **GetColumnBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |

---

### Method Details

#### FillColumn

**FillColumn**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF, **cornerRadius**: StiCornerRadius, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **interaction**: [StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md), **tooltip**: string, **elementIndex**: int): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  
- **cornerRadius** (StiCornerRadius)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **interaction** ([StiInteractionDataGeom](../Stimulsoft/Base/Context/StiInteractionDataGeom.md))  
- **tooltip** (string)  
- **elementIndex** (int)  


---

#### GetAreaBrush

**GetAreaBrush**(**color**: Color): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **color** (Color)  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### GetColorByIndex

**GetColorByIndex**(**index**: int, **count**: int, ****: ColorseriesColors): Color

**Parameters**

- **index** (int)  
- **count** (int)  
- **** (ColorseriesColors)  

**Returns** Color


---

#### GetColorBySeries

**GetColorBySeries**(**series**: IStiSeries, ****: ColorseriesColors): Color

**Parameters**

- **series** (IStiSeries)  
- **** (ColorseriesColors)  

**Returns** Color


---

#### GetColors

**GetColors**(**seriesCount**: int, ****: ColorseriesColors): Color[]

**Parameters**

- **seriesCount** (int)  
- **** (ColorseriesColors)  

**Returns** Color[]


---

#### GetColumnBorder

**GetColumnBorder**(**color**: Color): Color

**Parameters**

- **color** (Color)  

**Returns** Color


---

#### GetColumnBrush

**GetColumnBrush**(**color**: Color): [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **color** (Color)  

**Returns** [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md)


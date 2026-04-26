---
title: "StiProgressVisual Class"
---

## StiProgressVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Progress`

This is a base class to work with the progress element visualization.

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiProgressVisual**(StiProgressElement element, List<[StiProgressIteration](StiProgressIteration.md)> iterations) |  |

**StiProgressVisual**(**element**: StiProgressElement, **iterations**: List<[StiProgressIteration](StiProgressIteration.md)>)

**Parameters**

- **element** (StiProgressElement)  
- **iterations** (List<[StiProgressIteration](StiProgressIteration.md)>)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Element** | StiProgressElement |  |
| **Iterations** | List<[StiProgressIteration](StiProgressIteration.md)> |  |
| **MinElementSide** | byte |  |
| **MinFontSize** | byte |  |
| **Style** | [StiProgressElementStyle](../../../Stimulsoft_Report/Dashboard/Styles/StiProgressElementStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetColor** | Color |  |
| **GetColors** | Color[] |  |
| **GetDisplayText** | string |  |
| **GetInteractionDataGeom** | [StiInteractionDataGeom](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiInteractionDataGeom.md) |  |
| **GetTargetValues** | List<decimal> |  |
| **GetTextValues** | List<string> |  |
| **ProcessColor** | Color |  |
| **ProcessFontName** | string |  |
| **ProcessFontStyle** | FontStyle |  |
| **ProcessForeColor** | Color |  |
| **ProcessTrackColor** | Color |  |

---

### Method Details

#### GetColor

**GetColor**(**index**: int): Color

**Parameters**

- **index** (int)  

**Returns** Color


---

#### GetColors

**GetColors**(**seriesCount**: int): Color[]

**Parameters**

- **seriesCount** (int)  

**Returns** Color[]


---

#### GetDisplayText

**GetDisplayText**(**iteration**: [StiProgressIteration](StiProgressIteration.md), **valuePercent**: decimal): string

**Parameters**

- **iteration** ([StiProgressIteration](StiProgressIteration.md))  
- **valuePercent** (decimal)  

**Returns** string


---

#### GetInteractionDataGeom

**GetInteractionDataGeom**(**iteration**: [StiProgressIteration](StiProgressIteration.md)): [StiInteractionDataGeom](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiInteractionDataGeom.md)

**Parameters**

- **iteration** ([StiProgressIteration](StiProgressIteration.md))  

**Returns** [StiInteractionDataGeom](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiInteractionDataGeom.md)


---

#### GetTargetValues

**GetTargetValues**(): List<decimal>

**Returns** List<decimal>


---

#### GetTextValues

**GetTextValues**(): List<string>

**Returns** List<string>


---

#### ProcessColor

**ProcessColor**(**color**: Color, **iteration**: [StiProgressIteration](StiProgressIteration.md)): Color

**Parameters**

- **color** (Color)  
- **iteration** ([StiProgressIteration](StiProgressIteration.md))  

**Returns** Color


---

#### ProcessFontName

**ProcessFontName**(**fontName**: string, **iteration**: [StiProgressIteration](StiProgressIteration.md)): string

**Parameters**

- **fontName** (string)  
- **iteration** ([StiProgressIteration](StiProgressIteration.md))  

**Returns** string


---

#### ProcessFontStyle

**ProcessFontStyle**(**fontText**: [Font](../../../Stimulsoft_Drawing/root/Font.md), **iteration**: [StiProgressIteration](StiProgressIteration.md)): FontStyle

**Parameters**

- **fontText** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  
- **iteration** ([StiProgressIteration](StiProgressIteration.md))  

**Returns** FontStyle


---

#### ProcessForeColor

**ProcessForeColor**(**iteration**: [StiProgressIteration](StiProgressIteration.md), **defaultColor**: Color?): Color

**Parameters**

- **iteration** ([StiProgressIteration](StiProgressIteration.md))  
- **defaultColor** (Color?)  

**Returns** Color


---

#### ProcessTrackColor

**ProcessTrackColor**(**color**: Color, **iteration**: [StiProgressIteration](StiProgressIteration.md)): Color

**Parameters**

- **color** (Color)  
- **iteration** ([StiProgressIteration](StiProgressIteration.md))  

**Returns** Color


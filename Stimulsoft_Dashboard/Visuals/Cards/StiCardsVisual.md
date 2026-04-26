---
title: "StiCardsVisual Class"
---

## StiCardsVisual Class

**Namespace:** `Stimulsoft.Dashboard.Visuals.Cards`

### Inheritance

Inherits from: [StiVisual](../StiVisual.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCardsVisual**(StiCardsElement element, [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |

**StiCardsVisual**(**element**: StiCardsElement, **dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (StiCardsElement)  
- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataTable** | [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Element** | StiCardsElement |  |
| **Style** | StiCardsElementStyle |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws a visual object on specified context and at specified location. |
| **DrawEmptyData** | void |  |
| **GetColor** | Color |  |
| **GetStyleColor** | Color |  |
| **MeasureBubbleCell** | SizeF |  |
| **MeasureDataBarsCell** | SizeF |  |
| **MeasureIndicatorCell** `static` | SizeF |  |
| **MeasureSparklinesCell** `static` | SizeF |  |
| **ProcessColumnsWithTopN** | List<object[]> |  |
| **UnionRectangles** `static` | [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **ZoomAndMoveUp** `static` | List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)> |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): void

Draws a visual object on specified context and at specified location.

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  


---

#### DrawEmptyData

**DrawEmptyData**(**g**: [Graphics](../../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF): void

**Parameters**

- **g** ([Graphics](../../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  


---

#### GetColor

**GetColor**(**index**: int): Color

**Parameters**

- **index** (int)  

**Returns** Color


---

#### GetStyleColor

**GetStyleColor**(**index**: int): Color

**Parameters**

- **index** (int)  

**Returns** Color


---

#### MeasureBubbleCell

**MeasureBubbleCell**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **cards**: StiCardsElement, **column**: StiCardsColumn, **rowValue**: object, **zoom**: float): SizeF

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **cards** (StiCardsElement)  
- **column** (StiCardsColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** SizeF


---

#### MeasureDataBarsCell

**MeasureDataBarsCell**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **cards**: StiCardsElement, **column**: StiCardsColumn, **rowValue**: object, **zoom**: float): SizeF

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **cards** (StiCardsElement)  
- **column** (StiCardsColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** SizeF


---

#### MeasureIndicatorCell `static`

**MeasureIndicatorCell**(**context**: [StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md), **cards**: StiCardsElement, **column**: StiCardsColumn, **rowValue**: object, **zoom**: float): SizeF

**Parameters**

- **context** ([StiContext](../../../Stimulsoft_Report/Stimulsoft/Base/Context/StiContext.md))  
- **cards** (StiCardsElement)  
- **column** (StiCardsColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** SizeF


---

#### MeasureSparklinesCell `static`

**MeasureSparklinesCell**(**sparklinesCardsColumn**: StiSparklinesCardsColumn, **zoom**: float): SizeF

**Parameters**

- **sparklinesCardsColumn** (StiSparklinesCardsColumn)  
- **zoom** (float)  

**Returns** SizeF


---

#### ProcessColumnsWithTopN

**ProcessColumnsWithTopN**(**columns**: List<StiCardsColumn>): List<object[]>

**Parameters**

- **columns** (List<StiCardsColumn>)  

**Returns** List<object[]>


---

#### UnionRectangles `static`

**UnionRectangles**(**rectangles**: List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>): [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **rectangles** (List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>)  

**Returns** [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### ZoomAndMoveUp `static`

**ZoomAndMoveUp**(**rectangles**: List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>, **zoomHeight**: double): List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>

**Parameters**

- **rectangles** (List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>)  
- **zoomHeight** (double)  

**Returns** List<[RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)>


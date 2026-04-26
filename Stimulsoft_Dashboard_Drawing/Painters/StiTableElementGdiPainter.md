---
title: "StiTableElementGdiPainter Class"
---

## StiTableElementGdiPainter Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters`

### Inheritance

Inherits from: [StiElementGdiPainter](StiElementGdiPainter.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **MeasureBubbleCell** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **MeasureDataBarsCell** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **MeasureIndicatorCell** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **MeasureSparklinesCell** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **PaintCheckBoxTitle** | void |  |
| **PaintContent** | void |  |
| **PaintFrozenArea** `static` | void |  |
| **ProcessColumnsWithTopN** `static` | List<object[]> |  |

---

### Method Details

#### MeasureBubbleCell `static`

**MeasureBubbleCell**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **table**: StiTableElement, **column**: StiTableColumn, **rowValue**: object, **zoom**: float): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **table** (StiTableElement)  
- **column** (StiTableColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


---

#### MeasureDataBarsCell `static`

**MeasureDataBarsCell**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **table**: StiTableElement, **column**: StiTableColumn, **rowValue**: object, **zoom**: float): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **table** (StiTableElement)  
- **column** (StiTableColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


---

#### MeasureIndicatorCell `static`

**MeasureIndicatorCell**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **table**: StiTableElement, **column**: StiTableColumn, **rowValue**: object, **zoom**: float): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **table** (StiTableElement)  
- **column** (StiTableColumn)  
- **rowValue** (object)  
- **zoom** (float)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


---

#### MeasureSparklinesCell `static`

**MeasureSparklinesCell**(**table**: StiTableElement, **columnWidth**: double, **zoom**: float): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **table** (StiTableElement)  
- **columnWidth** (double)  
- **zoom** (float)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


---

#### PaintCheckBoxTitle

**PaintCheckBoxTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintContent

**PaintContent**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **element**: IStiElement): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **element** (IStiElement)  


---

#### PaintFrozenArea `static`

**PaintFrozenArea**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **table**: StiTableElement, **column**: StiTableColumn): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **table** (StiTableElement)  
- **column** (StiTableColumn)  


---

#### ProcessColumnsWithTopN `static`

**ProcessColumnsWithTopN**(**dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **columns**: List<StiTableColumn>): List<object[]>

**Parameters**

- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **columns** (List<StiTableColumn>)  

**Returns** List<object[]>


---
title: "StiBarCodeExportPainter Class"
---

## StiBarCodeExportPainter Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: [Stimulsoft.Report.Painters.IStiBarCodePainter](../Painters/IStiBarCodePainter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBarCodeExportPainter**([StiSvgGeomWriter](StiSvgGeomWriter.md) geomWriter) |  |
| **StiBarCodeExportPainter**([StiPdfGeomWriter](StiPdfGeomWriter.md) geomWriter) |  |
| **StiBarCodeExportPainter**([StiExcel2007GeomWriter](StiExcel2007GeomWriter.md) geomWriter) |  |

**StiBarCodeExportPainter**(**geomWriter**: [StiSvgGeomWriter](StiSvgGeomWriter.md))

**Parameters**

- **geomWriter** ([StiSvgGeomWriter](StiSvgGeomWriter.md))  

---

**StiBarCodeExportPainter**(**geomWriter**: [StiPdfGeomWriter](StiPdfGeomWriter.md))

**Parameters**

- **geomWriter** ([StiPdfGeomWriter](StiPdfGeomWriter.md))  

---

**StiBarCodeExportPainter**(**geomWriter**: [StiExcel2007GeomWriter](StiExcel2007GeomWriter.md))

**Parameters**

- **geomWriter** ([StiExcel2007GeomWriter](StiExcel2007GeomWriter.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BaseDrawImage** | void |  |
| **BaseDrawRectangle** | void |  |
| **BaseDrawString** | void |  |
| **BaseFillEllipse** | void |  |
| **BaseFillPolygon** | void |  |
| **BaseFillPolygons** | void |  |
| **BaseFillRectangle** | void |  |
| **BaseFillRectangle2D** | void |  |
| **BaseMeasureString** | SizeF |  |
| **BaseRollbackTransform** | void |  |
| **BaseTransform** | void |  |

---

### Method Details

#### BaseDrawImage

**BaseDrawImage**(**context**: object, **image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **report**: [StiReport](../root/StiReport.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **context** (object)  
- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### BaseDrawRectangle

**BaseDrawRectangle**(**context**: object, **penColor**: Color, **penSize**: float, **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **context** (object)  
- **penColor** (Color)  
- **penSize** (float)  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### BaseDrawString

**BaseDrawString**(**context**: object, **st**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **rect**: RectangleF, **sf**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)): void

**Parameters**

- **context** (object)  
- **st** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **rect** (RectangleF)  
- **sf** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  


---

#### BaseFillEllipse

**BaseFillEllipse**(**context**: object, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **context** (object)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### BaseFillPolygon

**BaseFillPolygon**(**context**: object, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), ****: PointFpoints): void

**Parameters**

- **context** (object)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **** (PointFpoints)  


---

#### BaseFillPolygons

**BaseFillPolygons**(**context**: object, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **points**: List<List<PointF>>, **rectf**: RectangleF?): void

**Parameters**

- **context** (object)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **points** (List<List<PointF>>)  
- **rectf** (RectangleF?)  


---

#### BaseFillRectangle

**BaseFillRectangle**(**context**: object, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **context** (object)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### BaseFillRectangle2D

**BaseFillRectangle2D**(**context**: object, **brush**: [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md), **x**: float, **y**: float, **width**: float, **height**: float): void

**Parameters**

- **context** (object)  
- **brush** ([StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **x** (float)  
- **y** (float)  
- **width** (float)  
- **height** (float)  


---

#### BaseMeasureString

**BaseMeasureString**(**context**: object, **st**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): SizeF

**Parameters**

- **context** (object)  
- **st** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

**Returns** SizeF


---

#### BaseRollbackTransform

**BaseRollbackTransform**(**context**: object): void

**Parameters**

- **context** (object)  


---

#### BaseTransform

**BaseTransform**(**context**: object, **x**: float, **y**: float, **angle**: float, **dx**: float, **dy**: float): void

**Parameters**

- **context** (object)  
- **x** (float)  
- **y** (float)  
- **angle** (float)  
- **dx** (float)  
- **dy** (float)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **OnlyAssembleData** | bool |  |

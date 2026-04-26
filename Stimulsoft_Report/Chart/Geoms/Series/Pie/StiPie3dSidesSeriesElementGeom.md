---
title: "StiPie3dSidesSeriesElementGeom Class"
---

## StiPie3dSidesSeriesElementGeom Class

**Namespace:** `Stimulsoft.Report.Chart.Geoms.Series.Pie`

### Inheritance

Inherits from: StiSeriesElementGeom  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pie3DSlice** | [StiPie3dSlice](../../../StiPie3dSlice.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** | bool |  |
| **CreateBrushForPeriphery** | [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CreateBrushForSide** | [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CreateColorWithCorrectedLightness** `static` | Color |  |
| **CreateSurfaceBrushes** | void |  |
| **Draw** | void |  |
| **DrawCylinderSurfaceSection** | void |  |
| **GetActualAngle** | float |  |
| **GetTextPosition** | PointF |  |
| **PeripheralPoint** | PointF |  |
| **TransformAngle** | float |  |

---

### Method Details

#### Contains

**Contains**(**px**: float, **py**: float): bool

**Parameters**

- **px** (float)  
- **py** (float)  

**Returns** bool


---

#### CreateBrushForPeriphery

**CreateBrushForPeriphery**(**color**: Color): [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **color** (Color)  

**Returns** [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### CreateBrushForSide

**CreateBrushForSide**(**color**: Color, **angle**: double): [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **color** (Color)  
- **angle** (double)  

**Returns** [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### CreateColorWithCorrectedLightness `static`

**CreateColorWithCorrectedLightness**(**color**: Color, **correctionFactor**: float): Color

**Parameters**

- **color** (Color)  
- **correctionFactor** (float)  

**Returns** Color


---

#### CreateSurfaceBrushes

**CreateSurfaceBrushes**(**shadowStyle**: [StiPie3dLightingStyle](../../../StiPie3dLightingStyle.md)): void

**Parameters**

- **shadowStyle** ([StiPie3dLightingStyle](../../../StiPie3dLightingStyle.md))  


---

#### Draw

**Draw**(**context**: [StiContext](../../../../Stimulsoft/Base/Context/StiContext.md)): void

**Parameters**

- **context** ([StiContext](../../../../Stimulsoft/Base/Context/StiContext.md))  


---

#### DrawCylinderSurfaceSection

**DrawCylinderSurfaceSection**(**context**: [StiContext](../../../../Stimulsoft/Base/Context/StiContext.md), **pen**: [StiPenGeom](../../../../Stimulsoft/Base/Context/StiPenGeom.md), **brush**: [StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md), **peripherySurfaceBounds**: [StiPie3dPeripherySurfaceBounds](../../../StiPie3dPeripherySurfaceBounds.md)): void

**Parameters**

- **context** ([StiContext](../../../../Stimulsoft/Base/Context/StiContext.md))  
- **pen** ([StiPenGeom](../../../../Stimulsoft/Base/Context/StiPenGeom.md))  
- **brush** ([StiBrush](../../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **peripherySurfaceBounds** ([StiPie3dPeripherySurfaceBounds](../../../StiPie3dPeripherySurfaceBounds.md))  


---

#### GetActualAngle

**GetActualAngle**(**transformedAngle**: float): float

**Parameters**

- **transformedAngle** (float)  

**Returns** float


---

#### GetTextPosition

**GetTextPosition**(): PointF

**Returns** PointF


---

#### PeripheralPoint

**PeripheralPoint**(**xCenter**: float, **yCenter**: float, **semiMajor**: float, **semiMinor**: float, **angleDegrees**: float): PointF

**Parameters**

- **xCenter** (float)  
- **yCenter** (float)  
- **semiMajor** (float)  
- **semiMinor** (float)  
- **angleDegrees** (float)  

**Returns** PointF


---

#### TransformAngle

**TransformAngle**(**angle**: float): float

**Parameters**

- **angle** (float)  

**Returns** float


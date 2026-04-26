---
title: "StiAxisAreaCoreXF3D Class"
---

## StiAxisAreaCoreXF3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisAreaCoreXF3D**(IStiArea area) |  |

**StiAxisAreaCoreXF3D**(**area**: IStiArea)

**Parameters**

- **area** (IStiArea)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void | Applying specified style to this area. |
| **CheckShowEdgeValues** | void |  |
| **CheckStripLinesAndMaximumMinimumXAxis** | void | Gets minimum and maximum values if specified XAxis from calculated StripLines collection. |
| **CheckStripLinesAndMaximumMinimumYAxis** | void | Gets minimum and maximum values of specified YAxis from calculated StripLines collection. |
| **CheckStripLinesAndMaximumMinimumZAxis** | void | Gets minimum and maximum values if specified ZAxis from calculated StripLines collection. |
| **CreateStripLinesXAxis** | void | Creates Strip lines collection for XAxis. |
| **CreateStripLinesZAxis** | void | Creates Strip lines collection for ZAxis. |
| **GetDividerY** | double | Returns position on y of zero line for y axis. |
| **GetFactorWidthHeight** | double |  |
| **GetRedner3D** | [StiRender3D](StiRender3D.md) |  |
| **PrepareInfo** | void |  |
| **PrepareRange** | void |  |
| **Render** | StiCellGeom |  |
| **SwitchOff** | void | Internal use only. |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle): void

Applying specified style to this area.

**Parameters**

- **style** (IStiChartStyle)  


---

#### CheckShowEdgeValues

**CheckShowEdgeValues**(**axis**: [IStiXAxis3D](IStiXAxis3D.md)): void

**Parameters**

- **axis** ([IStiXAxis3D](IStiXAxis3D.md))  


---

#### CheckStripLinesAndMaximumMinimumXAxis

**CheckStripLinesAndMaximumMinimumXAxis**(**axis**: IStiAxis3D): void

Gets minimum and maximum values if specified XAxis from calculated StripLines collection.

**Parameters**

- **axis** (IStiAxis3D)  


---

#### CheckStripLinesAndMaximumMinimumYAxis

**CheckStripLinesAndMaximumMinimumYAxis**(**axis**: IStiAxis3D): void

Gets minimum and maximum values of specified YAxis from calculated StripLines collection.

**Parameters**

- **axis** (IStiAxis3D)  


---

#### CheckStripLinesAndMaximumMinimumZAxis

**CheckStripLinesAndMaximumMinimumZAxis**(**axis**: IStiAxis3D): void

Gets minimum and maximum values if specified ZAxis from calculated StripLines collection.

**Parameters**

- **axis** (IStiAxis3D)  


---

#### CreateStripLinesXAxis

**CreateStripLinesXAxis**(**axis**: IStiAxis3D): void

Creates Strip lines collection for XAxis.

**Parameters**

- **axis** (IStiAxis3D)  


---

#### CreateStripLinesZAxis

**CreateStripLinesZAxis**(**axis**: IStiAxis3D): void

Creates Strip lines collection for ZAxis.

**Parameters**

- **axis** (IStiAxis3D)  


---

#### GetDividerY

**GetDividerY**(): double

Returns position on y of zero line for y axis.

**Returns** double


---

#### GetFactorWidthHeight

**GetFactorWidthHeight**(**rect**: RectangleF): double

**Parameters**

- **rect** (RectangleF)  

**Returns** double


---

#### GetRedner3D

**GetRedner3D**(): [StiRender3D](StiRender3D.md)

**Returns** [StiRender3D](StiRender3D.md)


---

#### PrepareInfo

**PrepareInfo**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### PrepareRange

**PrepareRange**(**xAxis**: IStiAxis3D, **yAxis**: IStiAxis3D, **zAxis**: IStiAxis3D): void

**Parameters**

- **xAxis** (IStiAxis3D)  
- **yAxis** (IStiAxis3D)  
- **zAxis** (IStiAxis3D)  


---

#### Render

**Render**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom


---

#### SwitchOff

**SwitchOff**(): void

Internal use only.


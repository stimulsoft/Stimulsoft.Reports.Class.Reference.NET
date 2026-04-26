---
title: "StiChartTableCore Class"
---

## StiChartTableCore Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: ICloneable, [IStiApplyStyle](IStiApplyStyle.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiChartTableCore**(IStiChartTable table) |  |

**StiChartTableCore**(**table**: IStiChartTable)

**Parameters**

- **table** (IStiChartTable)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ChartTable** | IStiChartTable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void |  |
| **Clone** | object |  |
| **GetHeightHeaderTable** | float |  |
| **GetHeightTable** | float |  |
| **GetWidthCellLegend** | float |  |
| **Render** | StiCellGeom |  |
| **ShowTable** | bool |  |

---

### Method Details

#### ApplyStyle

**ApplyStyle**(**style**: IStiChartStyle): void

**Parameters**

- **style** (IStiChartStyle)  


---

#### Clone

**Clone**(): object

**Returns** object


---

#### GetHeightHeaderTable

**GetHeightHeaderTable**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **widthTable**: float): float

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **widthTable** (float)  

**Returns** float


---

#### GetHeightTable

**GetHeightTable**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **widthTable**: float): float

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **widthTable** (float)  

**Returns** float


---

#### GetWidthCellLegend

**GetWidthCellLegend**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): float

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  

**Returns** float


---

#### Render

**Render**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **rect**: RectangleF): StiCellGeom

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **rect** (RectangleF)  

**Returns** StiCellGeom


---

#### ShowTable

**ShowTable**(): bool

**Returns** bool


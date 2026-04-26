---
title: "StiAxisAreaCoreXF Class"
---

## StiAxisAreaCoreXF Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiAreaCoreXF  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisAreaCoreXF**(IStiArea area) |  |

**StiAxisAreaCoreXF**(**area**: IStiArea)

**Parameters**

- **area** (IStiArea)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BlockScrollValueX** | bool |  |
| **BlockScrollValueY** | bool |  |
| **ScrollDragStartValue** | double |  |
| **ScrollValueX** | double | Gets or sets left position of view area in scrollable area for Axis X. |
| **ScrollValueY** | double | Gets or sets left position of view area in scrollable area for Axis Y. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** | void | Applying specified style to this area. |
| **CheckShowEdgeValues** | void |  |
| **CheckStripLinesAndMaximumMinimumXAxis** | void | Gets minimum and maximum values if specified YAxis from calculated StripLines collection. |
| **CheckStripLinesAndMaximumMinimumYAxis** | void | Gets minimum and maximum values of specified XAxis from calculated StripLines collection. |
| **CreateStripLinesXAxis** | void | Creates Strip lines collection for XAxis. |
| **CreateStripLinesYAxis** | void | Creates Strip lines collection for YAxis. |
| **GetDividerRightY** | double | Returns position on right y of zero line for y axis. |
| **GetDividerTopX** | double | Returns position on x top of zero line for x axis. |
| **GetDividerX** | double | Returns position on x of zero line for x axis. |
| **GetDividerXD** | double |  |
| **GetDividerY** | double | Returns position on y of zero line for y axis. |
| **GetNextLowerDigit** `static` | double |  |
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

**CheckShowEdgeValues**(**axis**: IStiAxis): void

**Parameters**

- **axis** (IStiAxis)  


---

#### CheckStripLinesAndMaximumMinimumXAxis

**CheckStripLinesAndMaximumMinimumXAxis**(**axis**: IStiAxis): void

Gets minimum and maximum values if specified YAxis from calculated StripLines collection.

**Parameters**

- **axis** (IStiAxis)  


---

#### CheckStripLinesAndMaximumMinimumYAxis

**CheckStripLinesAndMaximumMinimumYAxis**(**axis**: IStiAxis): void

Gets minimum and maximum values of specified XAxis from calculated StripLines collection.

**Parameters**

- **axis** (IStiAxis)  


---

#### CreateStripLinesXAxis

**CreateStripLinesXAxis**(**axis**: IStiAxis): void

Creates Strip lines collection for XAxis.

**Parameters**

- **axis** (IStiAxis)  


---

#### CreateStripLinesYAxis

**CreateStripLinesYAxis**(**axis**: IStiAxis, **isDateTimeValues**: bool): void

Creates Strip lines collection for YAxis.

**Parameters**

- **axis** (IStiAxis)  
- **isDateTimeValues** (bool)  


---

#### GetDividerRightY

**GetDividerRightY**(): double

Returns position on right y of zero line for y axis.

**Returns** double


---

#### GetDividerTopX

**GetDividerTopX**(): double

Returns position on x top of zero line for x axis.

**Returns** double


---

#### GetDividerX

**GetDividerX**(): double

Returns position on x of zero line for x axis.

**Returns** double


---

#### GetDividerXD

**GetDividerXD**(): double

**Returns** double


---

#### GetDividerY

**GetDividerY**(): double

Returns position on y of zero line for y axis.

**Returns** double


---

#### GetNextLowerDigit `static`

**GetNextLowerDigit**(**number**: double): double

**Parameters**

- **number** (double)  

**Returns** double


---

#### PrepareInfo

**PrepareInfo**(**rect**: RectangleF): void

**Parameters**

- **rect** (RectangleF)  


---

#### PrepareRange

**PrepareRange**(**specXAxis**: IStiAxis, **specXTopAxis**: IStiAxis, **specYAxis**: IStiAxis, **specYRightAxis**: IStiAxis): void

**Parameters**

- **specXAxis** (IStiAxis)  
- **specXTopAxis** (IStiAxis)  
- **specYAxis** (IStiAxis)  
- **specYRightAxis** (IStiAxis)  


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


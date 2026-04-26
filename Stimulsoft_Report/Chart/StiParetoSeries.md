---
title: "StiParetoSeries Class"
---

## StiParetoSeries Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiSeries  
Implements: IStiParetoSeries  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiParetoSeries**() |  |

**StiParetoSeries**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowApplyBrushNegative** | bool |  |
| **AllowApplyColorNegative** | bool |  |
| **AllowApplyLineColor** | bool |  |
| **BorderColor** | Color |  |
| **BorderThickness** | int |  |
| **Brush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BrushNegative** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **CornerRadius** | StiCornerRadius |  |
| **Icon** | StiFontIcons? |  |
| **LabelsOffset** | int |  |
| **LineColorNegative** | Color |  |
| **ShowNulls** | bool |  |
| **ShowNullsAs** | [StiShowEmptyCellsAs](StiShowEmptyCellsAs.md) |  |
| **ShowZeros** | bool |  |
| **ShowZerosAs** | [StiShowEmptyCellsAs](StiShowEmptyCellsAs.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **CreateNew** | StiSeries |  |
| **GetDefaultAreaType** | Type |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### CreateNew

**CreateNew**(): StiSeries

**Returns** StiSeries


---

#### GetDefaultAreaType

**GetDefaultAreaType**(): Type

**Returns** Type


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


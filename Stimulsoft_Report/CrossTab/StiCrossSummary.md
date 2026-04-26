---
title: "StiCrossSummary Class"
---

## StiCrossSummary Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiCrossCell  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCrossSummary**() |  |

**StiCrossSummary**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Arguments** | Hashtable |  |
| **AspectRatio** | bool |  |
| **CrossColumnValue** | string |  |
| **CrossRowValue** | string |  |
| **ImageHorAlignment** | [StiHorAlignment](../../Stimulsoft_Base/Drawing/StiHorAlignment.md) |  |
| **ImageVertAlignment** | [StiVertAlignment](../../Stimulsoft_Base/Drawing/StiVertAlignment.md) |  |
| **IndexOfSelectValue** | int |  |
| **ShowPercents** | bool |  |
| **Stretch** | bool |  |
| **Summary** | [StiSummaryType](Core/StiSummaryType.md) |  |
| **SummaryCalculationMode** | [StiSummaryCalculationMode](../Components/StiSummaryCalculationMode.md) |  |
| **SummaryValues** | [StiSummaryValues](Core/StiSummaryValues.md) |  |
| **TooltipAsHyperlink** | bool |  |
| **UseStyleOfSummaryInColumnTotal** | bool |  |
| **UseStyleOfSummaryInRowTotal** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(**cloneProperties**: bool): object

**Parameters**

- **cloneProperties** (bool)  

**Returns** object


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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ComplexExpression** | bool |  |

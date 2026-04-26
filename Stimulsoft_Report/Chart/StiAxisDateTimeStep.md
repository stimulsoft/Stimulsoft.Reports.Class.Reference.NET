---
title: "StiAxisDateTimeStep Class"
---

## StiAxisDateTimeStep Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Implements: IStiAxisDateTimeStep  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAxisDateTimeStep**() |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues) |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues, bool interpolation) |  |
| **StiAxisDateTimeStep**([StiTimeDateStep](StiTimeDateStep.md) step, int numberOfValues, bool interpolation, [StiDateTimeStepAggregation](StiDateTimeStepAggregation.md) aggregation) |  |

**StiAxisDateTimeStep**()

---

**StiAxisDateTimeStep**(**step**: [StiTimeDateStep](StiTimeDateStep.md), **numberOfValues**: int)

**Parameters**

- **step** ([StiTimeDateStep](StiTimeDateStep.md))  
- **numberOfValues** (int)  

---

**StiAxisDateTimeStep**(**step**: [StiTimeDateStep](StiTimeDateStep.md), **numberOfValues**: int, **interpolation**: bool)

**Parameters**

- **step** ([StiTimeDateStep](StiTimeDateStep.md))  
- **numberOfValues** (int)  
- **interpolation** (bool)  

---

**StiAxisDateTimeStep**(**step**: [StiTimeDateStep](StiTimeDateStep.md), **numberOfValues**: int, **interpolation**: bool, **aggregation**: [StiDateTimeStepAggregation](StiDateTimeStepAggregation.md))

**Parameters**

- **step** ([StiTimeDateStep](StiTimeDateStep.md))  
- **numberOfValues** (int)  
- **interpolation** (bool)  
- **aggregation** ([StiDateTimeStepAggregation](StiDateTimeStepAggregation.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Aggregation** | [StiDateTimeStepAggregation](StiDateTimeStepAggregation.md) |  |
| **Interpolation** | bool |  |
| **NumberOfValues** | int |  |
| **Step** | [StiTimeDateStep](StiTimeDateStep.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


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


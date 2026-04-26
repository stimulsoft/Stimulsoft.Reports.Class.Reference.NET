---
title: "StiIconSetItem Class"
---

## StiIconSetItem Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiIconSetItem**() | Creates a new object of the type StiIconSetItem. |
| **StiIconSetItem**([StiIcon](StiIcon.md) icon, [StiIconSetOperation](StiIconSetOperation.md) operation, [StiIconSetValueType](StiIconSetValueType.md) valueType, float value) | Creates a new object of the type StiIconSetItem. |

**StiIconSetItem**()

Creates a new object of the type StiIconSetItem.

---

**StiIconSetItem**(**icon**: [StiIcon](StiIcon.md), **operation**: [StiIconSetOperation](StiIconSetOperation.md), **valueType**: [StiIconSetValueType](StiIconSetValueType.md), **value**: float)

Creates a new object of the type StiIconSetItem.

**Parameters**

- **icon** ([StiIcon](StiIcon.md))  
- **operation** ([StiIconSetOperation](StiIconSetOperation.md))  
- **valueType** ([StiIconSetValueType](StiIconSetValueType.md))  
- **value** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Icon** | [StiIcon](StiIcon.md) |  |
| **Operation** | [StiIconSetOperation](StiIconSetOperation.md) |  |
| **Value** | float |  |
| **ValueType** | [StiIconSetValueType](StiIconSetValueType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

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


---
title: "StiDataTransformationColumn Class"
---

## StiDataTransformationColumn Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Describes a data transformation column.

### Inheritance

Inherits from: StiDataColumn  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataTransformationColumn**() | Creates a new object of the type StiCalcDataColumn. |
| **StiDataTransformationColumn**(string name, string alias, Type type, string expression) |  |
| **StiDataTransformationColumn**(string name, string alias, Type type, string expression, string key, [StiDataTransformationMode](StiDataTransformationMode.md) mode) | Creates a new object of the type StiCalcDataColumn. |

**StiDataTransformationColumn**()

Creates a new object of the type StiCalcDataColumn.

---

**StiDataTransformationColumn**(**name**: string, **alias**: string, **type**: Type, **expression**: string)

**Parameters**

- **name** (string)  
- **alias** (string)  
- **type** (Type)  
- **expression** (string)  

---

**StiDataTransformationColumn**(**name**: string, **alias**: string, **type**: Type, **expression**: string, **key**: string, **mode**: [StiDataTransformationMode](StiDataTransformationMode.md))

Creates a new object of the type StiCalcDataColumn.

**Parameters**

- **name** (string) — Name of column.  
- **alias** (string) — Alias of column.  
- **type** (Type) — Type of data of column.  
- **expression** (string)  
- **key** (string) — Key string.  
- **mode** ([StiDataTransformationMode](StiDataTransformationMode.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expression** | string |  |
| **Mode** | [StiDataTransformationMode](StiDataTransformationMode.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDictionaryColumn** | StiDataColumn |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetDictionaryColumn

**GetDictionaryColumn**(): StiDataColumn

**Returns** StiDataColumn


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


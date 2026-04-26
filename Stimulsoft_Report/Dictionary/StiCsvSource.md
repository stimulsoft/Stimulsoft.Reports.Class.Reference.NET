---
title: "StiCsvSource Class"
---

## StiCsvSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiFileDataSource](StiFileDataSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCsvSource**() | Creates a new object of the type StiCsvSource. |
| **StiCsvSource**(string path, string name, string alias, int codePage) |  |
| **StiCsvSource**(string path, string name, string alias, int codePage, string separator) |  |
| **StiCsvSource**(string path, string name, string alias, int codePage, string separator, string key) |  |

**StiCsvSource**()

Creates a new object of the type StiCsvSource.

---

**StiCsvSource**(**path**: string, **name**: string, **alias**: string, **codePage**: int)

**Parameters**

- **path** (string)  
- **name** (string)  
- **alias** (string)  
- **codePage** (int)  

---

**StiCsvSource**(**path**: string, **name**: string, **alias**: string, **codePage**: int, **separator**: string)

**Parameters**

- **path** (string)  
- **name** (string)  
- **alias** (string)  
- **codePage** (int)  
- **separator** (string)  

---

**StiCsvSource**(**path**: string, **name**: string, **alias**: string, **codePage**: int, **separator**: string, **key**: string)

**Parameters**

- **path** (string)  
- **name** (string)  
- **alias** (string)  
- **codePage** (int)  
- **separator** (string)  
- **key** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConvertEmptyStringToNull** | bool |  |
| **Separator** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataAdapterType** | Type |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetDataAdapterType

**GetDataAdapterType**(): Type

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


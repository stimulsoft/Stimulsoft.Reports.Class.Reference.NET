---
title: "StiDBaseSource Class"
---

## StiDBaseSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiFileDataSource](StiFileDataSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDBaseSource**() | Creates a new object of the type StiDBaseSource. |
| **StiDBaseSource**(string path, string name, string alias, int codePage) |  |
| **StiDBaseSource**(string path, string name, string alias, int codePage, string key) |  |

**StiDBaseSource**()

Creates a new object of the type StiDBaseSource.

---

**StiDBaseSource**(**path**: string, **name**: string, **alias**: string, **codePage**: int)

**Parameters**

- **path** (string)  
- **name** (string)  
- **alias** (string)  
- **codePage** (int)  

---

**StiDBaseSource**(**path**: string, **name**: string, **alias**: string, **codePage**: int, **key**: string)

**Parameters**

- **path** (string)  
- **name** (string)  
- **alias** (string)  
- **codePage** (int)  
- **key** (string)  


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


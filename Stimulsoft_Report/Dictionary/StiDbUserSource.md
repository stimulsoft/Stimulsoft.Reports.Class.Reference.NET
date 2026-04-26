---
title: "StiDbUserSource Class"
---

## StiDbUserSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiDataStoreSource](StiDataStoreSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDbUserSource**() | Creates a new object of the type StiEditableUserSource. |
| **StiDbUserSource**(string name) | Creates a new object of the type StiEditableUserSource. |
| **StiDbUserSource**(string name, string alias) | Creates a new object of the type StiEditableUserSource. |
| **StiDbUserSource**(string name, string alias, string key) | Creates a new object of the type StiEditableUserSource. |

**StiDbUserSource**()

Creates a new object of the type StiEditableUserSource.

---

**StiDbUserSource**(**name**: string)

Creates a new object of the type StiEditableUserSource.

**Parameters**

- **name** (string) — Data Source name.  

---

**StiDbUserSource**(**name**: string, **alias**: string)

Creates a new object of the type StiEditableUserSource.

**Parameters**

- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  

---

**StiDbUserSource**(**name**: string, **alias**: string, **key**: string)

Creates a new object of the type StiEditableUserSource.

**Parameters**

- **name** (string) — Data Source name.  
- **alias** (string) — Data Source alias.  
- **key** (string) — Key string.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Data** | string |  |

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


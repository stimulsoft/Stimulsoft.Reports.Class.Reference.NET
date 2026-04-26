---
title: "StiGlobalizationItem Class"
---

## StiGlobalizationItem Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGlobalizationItem**() |  |
| **StiGlobalizationItem**(string propertyName, string text) |  |

**StiGlobalizationItem**()

---

**StiGlobalizationItem**(**propertyName**: string, **text**: string)

**Parameters**

- **propertyName** (string)  
- **text** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PropertyName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ToString** | string |  |

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


---

#### ToString

**ToString**(): string

**Returns** string


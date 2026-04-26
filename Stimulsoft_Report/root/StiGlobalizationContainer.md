---
title: "StiGlobalizationContainer Class"
---

## StiGlobalizationContainer Class

**Namespace:** `Stimulsoft.Report`

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGlobalizationContainer**() |  |
| **StiGlobalizationContainer**(string cultureName) |  |

**StiGlobalizationContainer**()

---

**StiGlobalizationContainer**(**cultureName**: string)

**Parameters**

- **cultureName** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CultureName** | string |  |
| **Items** | [StiGlobalizationItemCollection](StiGlobalizationItemCollection.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillItemsFromReport** | void |  |
| **GetAllStringsForReport** | Hashtable | Internal use only. |
| **LoadFromJsonObject** | void |  |
| **LocalizeReport** | void |  |
| **RemoveUnlocalizedItemsFromReport** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### FillItemsFromReport

**FillItemsFromReport**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### GetAllStringsForReport

**GetAllStringsForReport**(**report**: [StiReport](StiReport.md)): Hashtable

Internal use only.

**Parameters**

- **report** ([StiReport](StiReport.md)) — Report  

**Returns** Hashtable — Array of strings


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### LocalizeReport

**LocalizeReport**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### RemoveUnlocalizedItemsFromReport

**RemoveUnlocalizedItemsFromReport**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


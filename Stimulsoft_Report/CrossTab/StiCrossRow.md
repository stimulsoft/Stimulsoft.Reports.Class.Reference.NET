---
title: "StiCrossRow Class"
---

## StiCrossRow Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Inheritance

Inherits from: StiCrossHeader  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EnumeratorSeparator** | string |  |
| **EnumeratorType** | [StiEnumeratorType](Core/StiEnumeratorType.md) |  |
| **KeepMergedCellsTogether** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCrossRowTitle** | [StiCrossTitle](StiCrossTitle.md) |  |
| **GetCrossRowTotal** | [StiCrossRowTotal](StiCrossRowTotal.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### GetCrossRowTitle

**GetCrossRowTitle**(): [StiCrossTitle](StiCrossTitle.md)

**Returns** [StiCrossTitle](StiCrossTitle.md)


---

#### GetCrossRowTotal

**GetCrossRowTotal**(): [StiCrossRowTotal](StiCrossRowTotal.md)

**Returns** [StiCrossRowTotal](StiCrossRowTotal.md)


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


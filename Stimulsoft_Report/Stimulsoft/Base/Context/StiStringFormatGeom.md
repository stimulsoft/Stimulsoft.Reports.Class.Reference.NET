---
title: "StiStringFormatGeom Class"
---

## StiStringFormatGeom Class

**Namespace:** `Stimulsoft.Base.Context`

### Inheritance

Inherits from: [StiGeom](StiGeom.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiStringFormatGeom**([StringFormat](../../../../Stimulsoft_Drawing/root/StringFormat.md) sf) |  |

**StiStringFormatGeom**(**sf**: [StringFormat](../../../../Stimulsoft_Drawing/root/StringFormat.md))

**Parameters**

- **sf** ([StringFormat](../../../../Stimulsoft_Drawing/root/StringFormat.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alignment** | StringAlignment |  |
| **FormatFlags** | StringFormatFlags |  |
| **HotkeyPrefix** | HotkeyPrefix |  |
| **IsGeneric** | bool |  |
| **LineAlignment** | StringAlignment |  |
| **Trimming** | StringTrimming |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../../Stimulsoft_Base/Json/Linq/JObject.md)


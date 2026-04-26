---
title: "StiPdfDigitalSignature Class"
---

## StiPdfDigitalSignature Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiSignature  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfDigitalSignature**() | Creates a new component of the type StiPdfDigitalSignature. |
| **StiPdfDigitalSignature**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new component of the type StiPdfDigitalSignature. |

**StiPdfDigitalSignature**()

Creates a new component of the type StiPdfDigitalSignature.

---

**StiPdfDigitalSignature**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new component of the type StiPdfDigitalSignature.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Placeholder** | string |  |
| **SignatureImageBytes** | byte[] |  |

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


---
title: "StiPdfDigitalSignatureElement Class"
---

## StiPdfDigitalSignatureElement Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiSignature  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPdfDigitalSignatureElement**() | Creates a new component of the type StiPdfDigitalSignature. |
| **StiPdfDigitalSignatureElement**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new component of the type StiPdfDigitalSignature. |

**StiPdfDigitalSignatureElement**()

Creates a new component of the type StiPdfDigitalSignature.

---

**StiPdfDigitalSignatureElement**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new component of the type StiPdfDigitalSignature.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Appearance** | [StiPdfDigitalSignatureAppearanceType](StiPdfDigitalSignatureAppearanceType.md) |  |
| **BreakWord** | bool |  |
| **Options** | [StiPdfDigitalSignatureAppearanceOptions](StiPdfDigitalSignatureAppearanceOptions.md) |  |
| **RightToLeft** | bool |  |
| **SignatureDrawBytes** | byte[] |  |
| **SignatureImageBytes** | byte[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **RenderContent** | StiComponentsCollection |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### RenderContent

**RenderContent**(**certificate**: X509Certificate2, **dsReason**: string, **dsLocation**: string): StiComponentsCollection

**Parameters**

- **certificate** (X509Certificate2)  
- **dsReason** (string)  
- **dsLocation** (string)  

**Returns** StiComponentsCollection


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


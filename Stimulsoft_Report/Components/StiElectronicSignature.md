---
title: "StiElectronicSignature Class"
---

## StiElectronicSignature Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiSignature  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiElectronicSignature**() | Creates a new component of the type StiElectronicSignature. |
| **StiElectronicSignature**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new component of the type StiElectronicSignature. |

**StiElectronicSignature**()

Creates a new component of the type StiElectronicSignature.

---

**StiElectronicSignature**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new component of the type StiElectronicSignature.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCleanSignature** | bool |  |
| **AlreadySigned** | bool |  |
| **Description** | [IStiSignatureDescription](IStiSignatureDescription.md) |  |
| **Draw** | [IStiSignatureDraw](IStiSignatureDraw.md) |  |
| **Icon** | [IStiSignatureIcon](IStiSignatureIcon.md) |  |
| **Image** | [IStiSignatureImage](IStiSignatureImage.md) |  |
| **Mode** | [StiSignatureMode](StiSignatureMode.md) |  |
| **Text** | [IStiSignatureText](IStiSignatureText.md) |  |
| **Type** | [IStiSignatureType](IStiSignatureType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(**cloneProperties**: bool): object

Creates a new object that is a copy of the current instance.

**Parameters**

- **cloneProperties** (bool)  

**Returns** object — A new object that is a copy of this instance.


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


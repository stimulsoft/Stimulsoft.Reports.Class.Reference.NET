---
title: "StiElectronicSignature Class"
---

## StiElectronicSignature Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiElectronicSignature
```

### Inheritance

Inherits from: StiSignature  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiElectronicSignature()` | Creates a new component of the type StiElectronicSignature. |
| `StiElectronicSignature([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect)` | Creates a new component of the type StiElectronicSignature. |

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

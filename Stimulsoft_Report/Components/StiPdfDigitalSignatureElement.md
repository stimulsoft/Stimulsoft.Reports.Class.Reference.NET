---
title: "StiPdfDigitalSignatureElement Class"
---

## StiPdfDigitalSignatureElement Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPdfDigitalSignatureElement
```

### Inheritance

Inherits from: StiSignature  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPdfDigitalSignatureElement()` | Creates a new component of the type StiPdfDigitalSignature. |
| `StiPdfDigitalSignatureElement([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect)` | Creates a new component of the type StiPdfDigitalSignature. |

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

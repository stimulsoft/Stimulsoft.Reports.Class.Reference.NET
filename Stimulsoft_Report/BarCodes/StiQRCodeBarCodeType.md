---
title: "StiQRCodeBarCodeType Class"
---

## StiQRCodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

The class describes the Barcode type - QR Code.

```csharp
public class StiQRCodeBarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiQRCodeBarCodeType**() |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize) |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize, [Image](../../Stimulsoft_Drawing/Image.md) image) |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize, [Image](../../Stimulsoft_Drawing/Image.md) image, double imageMultipleFactor) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BodyBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **BodyShape** | [StiQRCodeBodyShapeType](StiQRCodeBodyShapeType.md) |  |
| **ErrorCorrectionLevel** | [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) |  |
| **EyeBallBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EyeBallShape** | [StiQRCodeEyeBallShapeType](StiQRCodeEyeBallShapeType.md) |  |
| **EyeFrameBrush** | [StiBrush](../../Stimulsoft_Base/Drawing/StiBrush.md) |  |
| **EyeFrameShape** | [StiQRCodeEyeFrameShapeType](StiQRCodeEyeFrameShapeType.md) |  |
| **Height** | float |  |
| **ImageBytes** | byte[] |  |
| **ImageMultipleFactor** | double |  |
| **MatrixSize** | [StiQRCodeSize](StiQRCodeSize.md) |  |
| **ProcessTilde** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyMaskPenaltyRule1** `static` | int |  |
| **ApplyMaskPenaltyRule2** `static` | int |  |
| **ApplyMaskPenaltyRule3** `static` | int |  |
| **ApplyMaskPenaltyRule4** `static` | int |  |
| **At** | int |  |
| **BuildMatrix** `static` | void |  |
| **CalculateBCHCode** `static` | int |  |
| **Clear** | void |  |
| **ClearMatrix** `static` | void |  |
| **Draw** | void |  |
| **EmbedBasicPatterns** `static` | void |  |
| **EmbedDataBits** `static` | void |  |
| **EmbedDataBits2** `static` | void |  |
| **EmbedTypeInfo** `static` | void |  |
| **FindMSBSet** `static` | int |  |
| **Get** | sbyte |  |
| **GetArray** | sbyte[][] |  |
| **GetBarcodeImage** `static` | [Image](../../Stimulsoft_Drawing/Image.md) |  |
| **GetDataMaskBit** `static` | bool |  |
| **GetECLevel** | ErrorCorrectionLevel |  |
| **GetHeight** | int |  |
| **GetMaskPattern** | int |  |
| **GetMatrixWidth** | int |  |
| **GetMode** | Mode |  |
| **GetNumDataBytes** | int |  |
| **GetNumECBytes** | int |  |
| **GetNumRSBlocks** | int |  |
| **GetNumTotalBytes** | int |  |
| **GetVersion** | int |  |
| **GetWidth** | int |  |
| **IsValid** | bool |  |
| **IsValidMaskPattern** `static` | bool |  |
| **LoadFromJsonObject** | void |  |
| **MakeTypeInfoBits** `static` | void |  |
| **MakeVersionInfoBits** `static` | void |  |
| **MaybeEmbedVersionInfo** `static` | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **Set** *(+1 overloads)* | void |  |
| **SetECLevel** | void |  |
| **SetMaskPattern** | void |  |
| **SetMatrixWidth** | void |  |
| **SetMode** | void |  |
| **SetNumDataBytes** | void |  |
| **SetNumECBytes** | void |  |
| **SetNumRSBlocks** | void |  |
| **SetNumTotalBytes** | void |  |
| **SetVersion** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **NUM_MASK_PATTERNS** | int |  |

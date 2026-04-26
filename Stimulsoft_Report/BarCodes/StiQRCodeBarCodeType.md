---
title: "StiQRCodeBarCodeType Class"
---

## StiQRCodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

The class describes the Barcode type - QR Code.

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiQRCodeBarCodeType**() |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize) |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize, [Image](../../Stimulsoft_Drawing/root/Image.md) image) |  |
| **StiQRCodeBarCodeType**(float module, [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md) errorCorrectionLevel, [StiQRCodeSize](StiQRCodeSize.md) matrixSize, [Image](../../Stimulsoft_Drawing/root/Image.md) image, double imageMultipleFactor) |  |

**StiQRCodeBarCodeType**()

---

**StiQRCodeBarCodeType**(**module**: float, **errorCorrectionLevel**: [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md), **matrixSize**: [StiQRCodeSize](StiQRCodeSize.md))

**Parameters**

- **module** (float)  
- **errorCorrectionLevel** ([StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md))  
- **matrixSize** ([StiQRCodeSize](StiQRCodeSize.md))  

---

**StiQRCodeBarCodeType**(**module**: float, **errorCorrectionLevel**: [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md), **matrixSize**: [StiQRCodeSize](StiQRCodeSize.md), **image**: [Image](../../Stimulsoft_Drawing/root/Image.md))

**Parameters**

- **module** (float)  
- **errorCorrectionLevel** ([StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md))  
- **matrixSize** ([StiQRCodeSize](StiQRCodeSize.md))  
- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  

---

**StiQRCodeBarCodeType**(**module**: float, **errorCorrectionLevel**: [StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md), **matrixSize**: [StiQRCodeSize](StiQRCodeSize.md), **image**: [Image](../../Stimulsoft_Drawing/root/Image.md), **imageMultipleFactor**: double)

**Parameters**

- **module** (float)  
- **errorCorrectionLevel** ([StiQRCodeErrorCorrectionLevel](StiQRCodeErrorCorrectionLevel.md))  
- **matrixSize** ([StiQRCodeSize](StiQRCodeSize.md))  
- **image** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **imageMultipleFactor** (double)  


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
| **GetBarcodeImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
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

---

### Method Details

#### ApplyMaskPenaltyRule1 `static`

**ApplyMaskPenaltyRule1**(**matrix**: ByteMatrix): int

**Parameters**

- **matrix** (ByteMatrix)  

**Returns** int


---

#### ApplyMaskPenaltyRule2 `static`

**ApplyMaskPenaltyRule2**(**matrix**: ByteMatrix): int

**Parameters**

- **matrix** (ByteMatrix)  

**Returns** int


---

#### ApplyMaskPenaltyRule3 `static`

**ApplyMaskPenaltyRule3**(**matrix**: ByteMatrix): int

**Parameters**

- **matrix** (ByteMatrix)  

**Returns** int


---

#### ApplyMaskPenaltyRule4 `static`

**ApplyMaskPenaltyRule4**(**matrix**: ByteMatrix): int

**Parameters**

- **matrix** (ByteMatrix)  

**Returns** int


---

#### At

**At**(**x**: int, **y**: int): int

**Parameters**

- **x** (int)  
- **y** (int)  

**Returns** int


---

#### BuildMatrix `static`

**BuildMatrix**(**dataBits**: BitVector, **ecLevel**: ErrorCorrectionLevel, **version**: int, **maskPattern**: int, **matrix**: ByteMatrix): void

**Parameters**

- **dataBits** (BitVector)  
- **ecLevel** (ErrorCorrectionLevel)  
- **version** (int)  
- **maskPattern** (int)  
- **matrix** (ByteMatrix)  


---

#### CalculateBCHCode `static`

**CalculateBCHCode**(**value**: int, **poly**: int): int

**Parameters**

- **value** (int)  
- **poly** (int)  

**Returns** int


---

#### Clear

**Clear**(**value**: sbyte): void

**Parameters**

- **value** (sbyte)  


---

#### ClearMatrix `static`

**ClearMatrix**(**matrix**: ByteMatrix): void

**Parameters**

- **matrix** (ByteMatrix)  


---

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **context** (object)  
- **barCode** (StiBarCode)  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### EmbedBasicPatterns `static`

**EmbedBasicPatterns**(**version**: int, **matrix**: ByteMatrix): void

**Parameters**

- **version** (int)  
- **matrix** (ByteMatrix)  


---

#### EmbedDataBits `static`

**EmbedDataBits**(**dataBits**: BitVector, **maskPattern**: int, **matrix**: ByteMatrix): void

**Parameters**

- **dataBits** (BitVector)  
- **maskPattern** (int)  
- **matrix** (ByteMatrix)  


---

#### EmbedDataBits2 `static`

**EmbedDataBits2**(**dataBits**: BitVector, **matrices**: List<ByteMatrix>): void

**Parameters**

- **dataBits** (BitVector)  
- **matrices** (List<ByteMatrix>)  


---

#### EmbedTypeInfo `static`

**EmbedTypeInfo**(**ecLevel**: ErrorCorrectionLevel, **maskPattern**: int, **matrix**: ByteMatrix): void

**Parameters**

- **ecLevel** (ErrorCorrectionLevel)  
- **maskPattern** (int)  
- **matrix** (ByteMatrix)  


---

#### FindMSBSet `static`

**FindMSBSet**(**value**: int): int

**Parameters**

- **value** (int)  

**Returns** int


---

#### Get

**Get**(**x**: int, **y**: int): sbyte

**Parameters**

- **x** (int)  
- **y** (int)  

**Returns** sbyte


---

#### GetArray

**GetArray**(): sbyte[][]

**Returns** sbyte[][]


---

#### GetBarcodeImage `static`

**GetBarcodeImage**(**code**: string, **zoom**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **code** (string)  
- **zoom** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetDataMaskBit `static`

**GetDataMaskBit**(**maskPattern**: int, **x**: int, **y**: int): bool

**Parameters**

- **maskPattern** (int)  
- **x** (int)  
- **y** (int)  

**Returns** bool


---

#### GetECLevel

**GetECLevel**(): ErrorCorrectionLevel

**Returns** ErrorCorrectionLevel


---

#### GetHeight

**GetHeight**(): int

**Returns** int


---

#### GetMaskPattern

**GetMaskPattern**(): int

**Returns** int


---

#### GetMatrixWidth

**GetMatrixWidth**(): int

**Returns** int


---

#### GetMode

**GetMode**(): Mode

**Returns** Mode


---

#### GetNumDataBytes

**GetNumDataBytes**(): int

**Returns** int


---

#### GetNumECBytes

**GetNumECBytes**(): int

**Returns** int


---

#### GetNumRSBlocks

**GetNumRSBlocks**(): int

**Returns** int


---

#### GetNumTotalBytes

**GetNumTotalBytes**(): int

**Returns** int


---

#### GetVersion

**GetVersion**(): int

**Returns** int


---

#### GetWidth

**GetWidth**(): int

**Returns** int


---

#### IsValid

**IsValid**(): bool

**Returns** bool


---

#### IsValidMaskPattern `static`

**IsValidMaskPattern**(**maskPattern**: int): bool

**Parameters**

- **maskPattern** (int)  

**Returns** bool


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### MakeTypeInfoBits `static`

**MakeTypeInfoBits**(**ecLevel**: ErrorCorrectionLevel, **maskPattern**: int, **bits**: BitVector): void

**Parameters**

- **ecLevel** (ErrorCorrectionLevel)  
- **maskPattern** (int)  
- **bits** (BitVector)  


---

#### MakeVersionInfoBits `static`

**MakeVersionInfoBits**(**version**: int, **bits**: BitVector): void

**Parameters**

- **version** (int)  
- **bits** (BitVector)  


---

#### MaybeEmbedVersionInfo `static`

**MaybeEmbedVersionInfo**(**version**: int, **matrix**: ByteMatrix): void

**Parameters**

- **version** (int)  
- **matrix** (ByteMatrix)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### Set

**Set**(**x**: int, **y**: int, **value**: sbyte): void

**Parameters**

- **x** (int)  
- **y** (int)  
- **value** (sbyte)  

---

**Set**(**x**: int, **y**: int, **value**: int): void

**Parameters**

- **x** (int)  
- **y** (int)  
- **value** (int)  


---

#### SetECLevel

**SetECLevel**(**value**: ErrorCorrectionLevel): void

**Parameters**

- **value** (ErrorCorrectionLevel)  


---

#### SetMaskPattern

**SetMaskPattern**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetMatrixWidth

**SetMatrixWidth**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetMode

**SetMode**(**value**: Mode): void

**Parameters**

- **value** (Mode)  


---

#### SetNumDataBytes

**SetNumDataBytes**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetNumECBytes

**SetNumECBytes**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetNumRSBlocks

**SetNumRSBlocks**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetNumTotalBytes

**SetNumTotalBytes**(**value**: int): void

**Parameters**

- **value** (int)  


---

#### SetVersion

**SetVersion**(**value**: int): void

**Parameters**

- **value** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **NUM_MASK_PATTERNS** | int |  |

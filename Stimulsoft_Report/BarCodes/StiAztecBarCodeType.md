---
title: "StiAztecBarCodeType Class"
---

## StiAztecBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAztecBarCodeType**() |  |
| **StiAztecBarCodeType**(float module, int errorCorrectionLevel, [StiAztecSize](StiAztecSize.md) matrixSize, int codePage) |  |

**StiAztecBarCodeType**()

---

**StiAztecBarCodeType**(**module**: float, **errorCorrectionLevel**: int, **matrixSize**: [StiAztecSize](StiAztecSize.md), **codePage**: int)

**Parameters**

- **module** (float)  
- **errorCorrectionLevel** (int)  
- **matrixSize** ([StiAztecSize](StiAztecSize.md))  
- **codePage** (int)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CodeWords** | int | Number of data codewords |
| **IsCompact** | bool | Compact or full symbol indicator |
| **Layers** | int | Number of levels |
| **Matrix** | StiBarcodeUtils.BitMatrix | The symbol image |
| **MatrixSize** | [StiAztecSize](StiAztecSize.md) |  |
| **Size** | int | Size in pixels (width and height) |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | Token |  |
| **AddBinaryShift** | Token |  |
| **AddBinaryShiftChar** | State |  |
| **AppendBit** | void |  |
| **AppendBitArray** | void |  |
| **AppendBits** | void |  |
| **AppendFLGn** | State |  |
| **AppendTo** *(+2 overloads)* | void |  |
| **Draw** | void |  |
| **Encode** `static` *(+2 overloads)* | AztecCode |  |
| **EndBinaryShift** | State |  |
| **GetBarcodeImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **IsBetterThanOrEqualTo** | bool |  |
| **LatchAndAppend** | State |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShiftAndAppend** | State |  |
| **ToBitArray** | BitArray |  |

---

### Method Details

#### Add

**Add**(**value**: int, **bitCount**: int): Token

**Parameters**

- **value** (int)  
- **bitCount** (int)  

**Returns** Token


---

#### AddBinaryShift

**AddBinaryShift**(**start**: int, **byteCount**: int): Token

**Parameters**

- **start** (int)  
- **byteCount** (int)  

**Returns** Token


---

#### AddBinaryShiftChar

**AddBinaryShiftChar**(**index**: int): State

**Parameters**

- **index** (int)  

**Returns** State


---

#### AppendBit

**AppendBit**(**bit**: bool): void

**Parameters**

- **bit** (bool)  


---

#### AppendBitArray

**AppendBitArray**(**other**: BitArray): void

**Parameters**

- **other** (BitArray)  


---

#### AppendBits

**AppendBits**(**value**: int, **numBits**: int): void

**Parameters**

- **value** (int)  
- **numBits** (int)  


---

#### AppendFLGn

**AppendFLGn**(**eci**: int): State

**Parameters**

- **eci** (int)  

**Returns** State


---

#### AppendTo

**AppendTo**(**bitArray**: BitArray, ****: bytetext): void

**Parameters**

- **bitArray** (BitArray)  
- **** (bytetext)  

---

**AppendTo**(**bitArray**: BitArray, ****: bytetext): void

**Parameters**

- **bitArray** (BitArray)  
- **** (bytetext)  

---

**AppendTo**(**bitArray**: BitArray, ****: bytetext): void

**Parameters**

- **bitArray** (BitArray)  
- **** (bytetext)  


---

#### Draw

**Draw**(**context**: object, **barCode**: StiBarCode, **rect**: RectangleF, **zoom**: float): void

**Parameters**

- **context** (object)  
- **barCode** (StiBarCode)  
- **rect** (RectangleF)  
- **zoom** (float)  


---

#### Encode `static`

**Encode**(**contents**: string, **eccPercent**: int, **layers**: [StiAztecSize](StiAztecSize.md), **codePage**: int, **useEci**: bool): AztecCode

**Parameters**

- **contents** (string)  
- **eccPercent** (int)  
- **layers** ([StiAztecSize](StiAztecSize.md))  
- **codePage** (int)  
- **useEci** (bool)  

**Returns** AztecCode

---

**Encode**(****: bytedata, **eci**: int, **minECCPercent**: int, **userSpecifiedLayers**: [StiAztecSize](StiAztecSize.md)): AztecCode

**Parameters**

- **** (bytedata)  
- **eci** (int)  
- **minECCPercent** (int)  
- **userSpecifiedLayers** ([StiAztecSize](StiAztecSize.md))  

**Returns** AztecCode

---

**Encode**(): BitArray

**Returns** BitArray


---

#### EndBinaryShift

**EndBinaryShift**(**index**: int): State

**Parameters**

- **index** (int)  

**Returns** State


---

#### GetBarcodeImage `static`

**GetBarcodeImage**(**code**: string, **zoom**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **code** (string)  
- **zoom** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### IsBetterThanOrEqualTo

**IsBetterThanOrEqualTo**(**other**: State): bool

**Parameters**

- **other** (State)  

**Returns** bool


---

#### LatchAndAppend

**LatchAndAppend**(**mode**: int, **value**: int): State

**Parameters**

- **mode** (int)  
- **value** (int)  

**Returns** State


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


---

#### ShiftAndAppend

**ShiftAndAppend**(**mode**: int, **value**: int): State

**Parameters**

- **mode** (int)  
- **value** (int)  

**Returns** State


---

#### ToBitArray

**ToBitArray**(****: bytetext): BitArray

**Parameters**

- **** (bytetext)  

**Returns** BitArray


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BinaryShiftByteCount** | int |  |
| **BitCount** | int |  |
| **EMPTY** | Token |  |
| **INITIAL_STATE** | State |  |
| **Mode** | int |  |
| **Previous** | Token |  |
| **Size** | int |  |
| **SizeInBytes** | int |  |
| **Token** | Token |  |

---
title: "StiAztecBarCodeType Class"
---

## StiAztecBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiAztecBarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiAztecBarCodeType()` |  |
| `StiAztecBarCodeType(float module, int errorCorrectionLevel, [StiAztecSize](StiAztecSize.md) matrixSize, int codePage)` |  |

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
| **GetBarcodeImage** `static` | [Image](../../Stimulsoft_Drawing/Image.md) |  |
| **IsBetterThanOrEqualTo** | bool |  |
| **LatchAndAppend** | State |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **ShiftAndAppend** | State |  |
| **ToBitArray** | BitArray |  |

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

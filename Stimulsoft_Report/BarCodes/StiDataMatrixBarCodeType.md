---
title: "StiDataMatrixBarCodeType Class"
---

## StiDataMatrixBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDataMatrixBarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiDataMatrixBarCodeType()` |  |
| `StiDataMatrixBarCodeType(float module, [StiDataMatrixEncodingType](StiDataMatrixEncodingType.md) encodingType, bool useRectangularSymbols, [StiDataMatrixSize](StiDataMatrixSize.md) matrixSize)` |  |
| `StiDataMatrixBarCodeType(float module, [StiDataMatrixEncodingType](StiDataMatrixEncodingType.md) encodingType, bool useRectangularSymbols, [StiDataMatrixSize](StiDataMatrixSize.md) matrixSize, bool processTilde)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EncodingType** | [StiDataMatrixEncodingType](StiDataMatrixEncodingType.md) |  |
| **MatrixSize** | [StiDataMatrixSize](StiDataMatrixSize.md) |  |
| **ProcessTilde** | bool |  |
| **UseRectangularSymbols** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Bytes** | int |  |
| **Datablock** | int |  |
| **ErrorMessage** | string |  |
| **FH** | int |  |
| **FW** | int |  |
| **Height** | int |  |
| **Height** | int |  |
| **Matrix** | byte[] |  |
| **RSblock** | int |  |
| **Width** | int |  |
| **Width** | int |  |

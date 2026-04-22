---
title: "StiPdf417BarCodeType Class"
---

## StiPdf417BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiPdf417BarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiPdf417BarCodeType()` |  |
| `StiPdf417BarCodeType(float module, [StiPdf417EncodingMode](StiPdf417EncodingMode.md) encodingMode, [StiPdf417ErrorsCorrectionLevel](StiPdf417ErrorsCorrectionLevel.md) errorsCorrectionLevel, int dataColumns, int dataRows, bool autoDataColumns, bool autoDataRows, float aspectRatio, int ratioY)` |  |
| `StiPdf417BarCodeType(float module, [StiPdf417EncodingMode](StiPdf417EncodingMode.md) encodingMode, [StiPdf417ErrorsCorrectionLevel](StiPdf417ErrorsCorrectionLevel.md) errorsCorrectionLevel, int dataColumns, int dataRows, bool autoDataColumns, bool autoDataRows, float aspectRatio, int ratioY, bool processTilde)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Addressee** | string |  |
| **AutoDataColumns** | bool |  |
| **AutoDataRows** | bool |  |
| **Checksum** | int? |  |
| **EncodingMode** | [StiPdf417EncodingMode](StiPdf417EncodingMode.md) |  |
| **ErrorMessage** | string |  |
| **ErrorsCorrectionLevel** | [StiPdf417ErrorsCorrectionLevel](StiPdf417ErrorsCorrectionLevel.md) |  |
| **FileId** | string | The same for each related PDF417 symbol |
| **FileName** | string |  |
| **FileSize** | long? |  |
| **Matrix** | byte[] | The raw image bits of the barcode |
| **MatrixHeight** | int |  |
| **MatrixWidth** | int | The number of X pixels of Matrix |
| **ProcessTilde** | bool |  |
| **SegmentCount** | int |  |
| **SegmentIndex** | int |  |
| **Sender** | string |  |
| **Timestamp** | long? |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddSegment** | void |  |
| **Draw** | void |  |
| **GetSegment** | DataSegment |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Length** | int |  |
| **Size** | int |  |
| **Start** | int |  |
| **Type** | DataSegmentType |  |

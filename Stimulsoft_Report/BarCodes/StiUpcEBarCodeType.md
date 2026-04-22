---
title: "StiUpcEBarCodeType Class"
---

## StiUpcEBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

The class describes the Barcode type - UPC-E.

```csharp
public class StiUpcEBarCodeType
```

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiUpcEBarCodeType()` |  |
| `StiUpcEBarCodeType(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **MakeUpcEBars** | List<EanBarInfo> |  |

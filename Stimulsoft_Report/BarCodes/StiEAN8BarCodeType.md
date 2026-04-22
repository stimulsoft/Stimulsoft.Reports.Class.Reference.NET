---
title: "StiEAN8BarCodeType Class"
---

## StiEAN8BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

The class describes the Barcode type - EAN-8.

```csharp
public class StiEAN8BarCodeType
```

### Inheritance

Inherits from: [StiEAN13BarCodeType](StiEAN13BarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiEAN8BarCodeType()` |  |
| `StiEAN8BarCodeType(float module, float height, [StiEanSupplementType](StiEanSupplementType.md) supplementType, string supplementCodeValue, bool showQuietZoneIndicator)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanLineHeightShort** | float |  |
| **EanMainHeight** | float |  |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **MakeEan8Bars** | List<EanBarInfo> |  |

---
title: "StiSSCC18BarCodeType Class"
---

## StiSSCC18BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

The class describes the Barcode type - Serial Shipping Container Code (SSCC-18).

```csharp
public class StiSSCC18BarCodeType
```

### Inheritance

Inherits from: [StiCode128cBarCodeType](StiCode128cBarCodeType.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSSCC18BarCodeType()` |  |
| `StiSSCC18BarCodeType(float module, float height)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CompanyPrefix** | string |  |
| **ExtensionDigit** | string |  |
| **SerialNumber** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **GetCombinedCode** | string |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

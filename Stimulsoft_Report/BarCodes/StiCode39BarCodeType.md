---
title: "StiCode39BarCodeType Class"
---

## StiCode39BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCode39BarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCode39BarCodeType**() |  |
| **StiCode39BarCodeType**(float module, float height, float ratio, [StiCheckSum](StiCheckSum.md) checkSum) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CheckSum** | [StiCheckSum](StiCheckSum.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CodeToBar** | string |  |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Code39LineHeightForCut** | float |  |
| **Code39LineHeightLong** | float |  |
| **Code39LineHeightShort** | float |  |
| **Code39MainHeight** | float |  |
| **Code39SpaceBottom** | float |  |
| **Code39SpaceLeft** | float |  |
| **Code39SpaceRight** | float |  |
| **Code39SpaceTop** | float |  |
| **Code39StartStopSymbolIndex** | int |  |
| **Code39Symbols** | string |  |
| **Code39TextHeight** | float |  |
| **Code39TextPosition** | float |  |

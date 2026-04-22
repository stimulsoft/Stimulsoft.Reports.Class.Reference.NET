---
title: "StiCode11BarCodeType Class"
---

## StiCode11BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCode11BarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCode11BarCodeType()` |  |
| `StiCode11BarCodeType(float module, float height, [StiCode11CheckSum](StiCode11CheckSum.md) checksum)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Checksum** | [StiCode11CheckSum](StiCode11CheckSum.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Code11LineHeightForCut** | float |  |
| **Code11LineHeightLong** | float |  |
| **Code11LineHeightShort** | float |  |
| **Code11MainHeight** | float |  |
| **Code11SpaceBottom** | float |  |
| **Code11SpaceLeft** | float |  |
| **Code11SpaceRight** | float |  |
| **Code11SpaceTop** | float |  |
| **Code11StartStopSymbolIndex** | int |  |
| **Code11Symbols** | string |  |
| **Code11TextHeight** | float |  |
| **Code11TextPosition** | float |  |
| **defaultCode11Module** | float |  |

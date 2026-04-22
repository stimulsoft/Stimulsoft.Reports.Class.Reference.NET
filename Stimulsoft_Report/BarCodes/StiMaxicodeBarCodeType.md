---
title: "StiMaxicodeBarCodeType Class"
---

## StiMaxicodeBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMaxicodeBarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMaxicodeBarCodeType**() |  |
| **StiMaxicodeBarCodeType**([StiMaxicodeMode](StiMaxicodeMode.md) mode, int structuredAppendPosition, int structuredAppendTotal, bool processTilde) |  |
| **StiMaxicodeBarCodeType**([StiMaxicodeMode](StiMaxicodeMode.md) mode, int structuredAppendPosition, int structuredAppendTotal, bool processTilde, bool trimExcessData) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Mode** | [StiMaxicodeMode](StiMaxicodeMode.md) |  |
| **ProcessTilde** | bool |  |
| **StructuredAppendPosition** | int |  |
| **StructuredAppendTotal** | int |  |
| **TrimExcessData** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **GetEciEncoding** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ErrorMessage** | string |  |
| **Matrix** | byte[] |  |

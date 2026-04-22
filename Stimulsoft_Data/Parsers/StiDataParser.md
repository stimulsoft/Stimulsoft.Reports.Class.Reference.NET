---
title: "StiDataParser Class"
---

## StiDataParser Class

**Namespace:** `Stimulsoft.Data.Parsers`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class StiDataParser
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataParser**([IStiAppDictionary](../../Stimulsoft_Base/IStiAppDictionary.md) dictionary, DataTable table, List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)> meters) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Dictionary** | [IStiAppDictionary](../../Stimulsoft_Base/IStiAppDictionary.md) |  |
| **Dimensions** | [IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md)[] |  |
| **IsGrandTotal** | bool |  |
| **Meters** | IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)> |  |
| **Table** | DataTable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataColumnIndex** | int |  |
| **GetDimensionIndex** | int |  |
| **GetSystemVariableValue** | object |  |
| **GetVariableValue** | object |  |
| **IsSystemVariable** | bool |  |
| **IsVariable** | bool |  |
| **RunFunction** | object |  |

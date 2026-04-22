---
title: "StiFIMBarCodeType Class"
---

## StiFIMBarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFIMBarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFIMBarCodeType**() |  |
| **StiFIMBarCodeType**(float module, float height, bool addClearZone) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AddClearZone** | bool |  |
| **FIMSpaceLeft** | float |  |
| **FIMSpaceRight** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FIMLineHeightForCut** | float |  |
| **FIMLineHeightLong** | float |  |
| **FIMLineHeightShort** | float |  |
| **FIMMainHeight** | float |  |
| **FIMSpaceBottom** | float |  |
| **FIMSpaceTop** | float |  |
| **FIMSymbols** | string |  |
| **FIMTextHeight** | float |  |
| **FIMTextPosition** | float |  |
| **defaultFIMModule** | float |  |

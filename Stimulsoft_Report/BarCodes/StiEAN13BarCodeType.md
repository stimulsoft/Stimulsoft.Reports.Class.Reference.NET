---
title: "StiEAN13BarCodeType Class"
---

## StiEAN13BarCodeType Class

**Namespace:** `Stimulsoft.Report.BarCodes`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiEAN13BarCodeType
```

### Inheritance

Inherits from: StiBarCodeTypeService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEAN13BarCodeType**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EanLineHeightForCut** | float |  |
| **EanLineHeightLong** | float |  |
| **EanLineHeightShort** | float |  |
| **EanMainHeight** | float |  |
| **EanSpaceBeforeAdd** | float |  |
| **EanSpaceBottom** | float |  |
| **EanSpaceLeft** | float |  |
| **EanSpaceRight** | float |  |
| **EanSpaceTextTop** | float |  |
| **EanSpaceTop** | float |  |
| **EanTextHeight** | float |  |
| **EanTextPositionBottom** | float |  |
| **EanTextPositionTop** | float |  |
| **EanWideToNarrowRatio** | float |  |
| **ShowQuietZoneIndicator** | bool |  |
| **SupplementCode** | string |  |
| **SupplementType** | [StiEanSupplementType](StiEanSupplementType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws the bar code with the specified parameters. |
| **DrawEanBars** | void |  |
| **GetSymbolWidth** | float | Returns width of one symbol in module. |
| **IsSymbolSpace** | bool | Returns true is char is space. |
| **LoadFromJsonObject** | void |  |
| **MakeEan13Bars** | List<EanBarInfo> |  |
| **MakeEanAdd2Bars** | List<EanBarInfo> |  |
| **MakeEanAdd5Bars** | List<EanBarInfo> |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **makeLonger** | string |  |

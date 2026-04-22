---
title: "StiUnit Class"
---

## StiUnit Class

**Namespace:** `Stimulsoft.Report.Units`  
**Assembly:** `Stimulsoft.Report`

Report units.

```csharp
public abstract class StiUnit
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Factor** | double | Gets the ruler scale in hundredths of inch on the one step. |
| **RollerStep** | double | Gets ruler step. |
| **ShortName** | string | Gets the shor unit name. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertFromHInches** *(+5 overloads)* | double | Converts a value from hundredths of inch into units of this class. |
| **ConvertToHInches** *(+5 overloads)* | double | Converts a value from hundredths of inch into units of this class. |
| **GetUnitFromReportUnit** `static` | [StiUnit](StiUnit.md) |  |
| **LoadFromJsonObject** `static` | [StiUnit](StiUnit.md) |  |
| **SaveToJsonObject** `static` | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Centimeters** | [StiCentimetersUnit](StiCentimetersUnit.md) |  |
| **HundredthsOfInch** | [StiHundredthsOfInchUnit](StiHundredthsOfInchUnit.md) |  |
| **Inches** | [StiInchesUnit](StiInchesUnit.md) |  |
| **Millimeters** | [StiMillimetersUnit](StiMillimetersUnit.md) |  |

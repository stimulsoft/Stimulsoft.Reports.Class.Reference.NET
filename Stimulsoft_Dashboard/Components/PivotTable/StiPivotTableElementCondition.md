---
title: "StiPivotTableElementCondition Class"
---

## StiPivotTableElementCondition Class

**Namespace:** `Stimulsoft.Dashboard.Components.PivotTable`  
**Assembly:** `Stimulsoft.Dashboard`

```csharp
public class StiPivotTableElementCondition
```

### Inheritance

Implements: [IStiPivotTableElementCondition](../../../Stimulsoft_Report/Dashboard/IStiPivotTableElementCondition.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPivotTableElementCondition**() |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BackColor** | Color |  |
| **Condition** | Report.Components.StiFilterCondition |  |
| **ConditionType** | [StiPivotTableConditionType](../../../Stimulsoft_Report/Dashboard/StiPivotTableConditionType.md) |  |
| **DataType** | Report.Components.StiFilterDataType |  |
| **Font** | [Font](../../../Stimulsoft_Drawing/Font.md) |  |
| **Icon** | [StiFontIcons](../../../Stimulsoft_Base/Stimulsoft/Report/Helpers/StiFontIcons.md) |  |
| **IconAlignment** | [StiIconAlignment](../../../Stimulsoft_Report/Dashboard/StiIconAlignment.md) |  |
| **IconColor** | Color |  |
| **KeyValueMeter** | string |  |
| **MeasureField** | string |  |
| **Permissions** | [StiConditionPermissions](../../../Stimulsoft_Report/Components/StiConditionPermissions.md) |  |
| **TextColor** | Color |  |
| **TopNConditionCell** | bool |  |
| **TopNConditionHeader** | bool |  |
| **TopNConditionTotal** | bool |  |
| **TopNCount** | int |  |
| **TopNMode** | [StiDataTopNMode](../../../Stimulsoft_Data/Engine/StiDataTopNMode.md) |  |
| **Value** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetIcon** | byte[] |  |
| **GetUniqueCode** | int |  |
| **LoadFromJson** `static` | [StiPivotTableElementCondition](StiPivotTableElementCondition.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

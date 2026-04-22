---
title: "StiDialogInfo Class"
---

## StiDialogInfo Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiDialogInfo
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDialogInfo**() |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, stringkeys , stringvalues ) |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, string keysColumn, string valuesColumn) |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, stringkeys , stringvalues , boolcheckedStates ) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowUserValues** | bool |  |
| **BindingValue** | bool |  |
| **BindingValuesColumn** | string |  |
| **BindingVariable** | StiVariable |  |
| **CheckedColumn** | string |  |
| **CheckedStates** | bool[] |  |
| **DateTimeType** | [StiDateTimeType](StiDateTimeType.md) |  |
| **FilterExpression** | string |  |
| **ItemsInitializationType** | [StiItemsInitializationType](StiItemsInitializationType.md) |  |
| **Keys** | string[] |  |
| **KeysColumn** | string |  |
| **Mask** | string |  |
| **RememberSelection** | bool |  |
| **SortDirection** | [StiVariableSortDirection](StiVariableSortDirection.md) |  |
| **SortField** | [StiVariableSortField](StiVariableSortField.md) |  |
| **Validation** | string |  |
| **Values** | string[] |  |
| **ValuesBindingList** | List<object>[] |  |
| **ValuesColumn** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Convert** `static` | string |  |
| **GetAndParseDialogInfoItems** | List<StiDialogInfoItem> |  |
| **GetDialogInfoItems** | List<StiDialogInfoItem> |  |
| **LoadFromJsonObject** | void |  |
| **OrderBy** | List<StiDialogInfoItem> |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SetDialogInfoItems** | void |  |

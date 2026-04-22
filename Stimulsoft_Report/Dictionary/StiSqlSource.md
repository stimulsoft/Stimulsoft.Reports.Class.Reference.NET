---
title: "StiSqlSource Class"
---

## StiSqlSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSqlSource
```

### Inheritance

Inherits from: [StiDataTableSource](StiDataTableSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiSqlSource()` | Creates a new object of the type StiSqlSource. |
| `StiSqlSource(string nameInSource, string name)` | Creates a new object of the type StiSqlSource. |
| `StiSqlSource(string nameInSource, string name, string alias)` | Creates a new object of the type StiSqlSource. |
| `StiSqlSource(string nameInSource, string name, string alias, string sqlCommand)` | Creates a new object of the type StiSqlSource. |
| `StiSqlSource(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowExpressions** | bool |  |
| **CommandTimeout** | int |  |
| **DataAdapter** | IDbDataAdapter |  |
| **SqlCommand** | string |  |
| **Type** | [StiSqlSourceType](StiSqlSourceType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddParameter** | StiDataParameter |  |
| **ConvertDbTypeToType** | Type | Internal use only. |
| **ConvertDbTypeToTypeInternal** | Type |  |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **Disconnect** | void |  |
| **GetDataAdapterType** | Type |  |
| **GetFinalSqlCommand** | string |  |
| **GetParameterTypesEnum** | Type |  |
| **GetSqlFilterQuery** | string |  |
| **LoadFromJsonObject** | void |  |
| **RetrieveData** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **UpdateParameters** | void |  |

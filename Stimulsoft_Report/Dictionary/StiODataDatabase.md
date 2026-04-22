---
title: "StiODataDatabase Class"
---

## StiODataDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiODataDatabase
```

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiODataDatabase()` | Creates a new object of the type StiODataDatabase. |
| `StiODataDatabase(string name, string connectionString)` | Creates a new object of the type StiODataDatabase. |
| `StiODataDatabase(string name, string alias, string connectionString)` | Creates a new object of the type StiODataDatabase. |
| `StiODataDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword)` | Creates a new object of the type StiODataDatabase. |
| `StiODataDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key)` | Creates a new object of the type StiODataDatabase. |
| `StiODataDatabase(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key, [StiODataVersion](../../Stimulsoft_Base/StiODataVersion.md) version)` | Creates a new object of the type StiODataDatabase. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CookieContainer** | CookieContainer |  |
| **Headers** | NameValueCollection |  |
| **Version** | [StiODataVersion](../../Stimulsoft_Base/StiODataVersion.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) | Returns full database information. |
| **LoadFromJsonObject** | void |  |
| **MapUserNameAndPassword** | string |  |
| **RegData** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

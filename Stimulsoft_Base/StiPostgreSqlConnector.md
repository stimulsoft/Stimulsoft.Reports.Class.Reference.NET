---
title: "StiPostgreSqlConnector Class"
---

## StiPostgreSqlConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiPostgreSqlConnector
```

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPostgreSqlConnector**(string connectionString) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowDevart** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **Get** `static` | [StiPostgreSqlConnector](StiPostgreSqlConnector.md) |  |
| **GetDatabaseSpecificName** | string |  |
| **GetFamilyConnectors** | [StiDataConnector](StiDataConnector.md)[] | Return an array of the data connectors which can be used also to access data for this type of the connector. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **LoadDevartConnector** `static` | [StiPostgreSqlDevartConnector](StiPostgreSqlDevartConnector.md) |  |
| **LoadGenericConnector** `static` | [StiPostgreSqlConnector](StiPostgreSqlConnector.md) |  |
| **ResetSettings** | void |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

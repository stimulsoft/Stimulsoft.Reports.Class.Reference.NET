---
title: "StiOleDbConnector Class"
---

## StiOleDbConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiOleDbConnector
```

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOleDbConnector**(string connectionString) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateAdapter** | DbDataAdapter | Returns new data adapter to this type of the database. |
| **CreateCommand** | DbCommand | Returns new data command for this type of the database. |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **Get** `static` | [StiOleDbConnector](StiOleDbConnector.md) |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetDbType** | Type | Returns the type of the DBType. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetRelationsTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

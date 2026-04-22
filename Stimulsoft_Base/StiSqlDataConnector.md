---
title: "StiSqlDataConnector Class"
---

## StiSqlDataConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class StiSqlDataConnector
```

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSqlDataConnector**(string connectionString) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string | Gets connection string to the database. |
| **DefaultSqlType** | int | Gets the default value of the data parameter. |
| **FolderAssembly** | string |  |
| **MethodDeriveParameters** | string |  |
| **NameAssembly** | string |  |
| **SqlType** | Type | Gets the type of an enumeration which describes data types. |
| **TypeCommand** | string |  |
| **TypeCommandBuilder** | string |  |
| **TypeConnection** | string |  |
| **TypeConnectionStringBuilder** | string |  |
| **TypeDataAdapter** | string |  |
| **TypeDataSourceEnumerator** | string |  |
| **TypeDbType** | string |  |
| **TypeParameter** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseConnection** | void | Closes specified connection. |
| **CreateAdapter** | DbDataAdapter | Returns new data adapter to this type of the database. |
| **CreateCommand** | DbCommand | Returns new data command for this type of the database. |
| **CreateCommandBuilder** | DbCommandBuilder | Returns new CommandBuilder. |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **CreateConnectionStringBuilder** | DbConnectionStringBuilder | Returns new ConnectionStringBuilder. |
| **CreateDataSourceEnumerator** | DbDataSourceEnumerator | Returns new DataSourceEnumerator. |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **ExecuteNonQuery** | void |  |
| **ExecuteReader** | DbDataReader |  |
| **FillAdapter** *(+1 overloads)* | void |  |
| **FillSchemaAdapter** | void |  |
| **Get** `static` | [StiSqlDataConnector](StiSqlDataConnector.md) |  |
| **GetDataTable** | DataTable |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetDbType** | Type | Returns the type of the DBType. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetParametersTable** | DataTable |  |
| **GetRelationsTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSchema** | DataTable |  |
| **GetSchemaTable** | DataTable |  |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **OpenConnection** | void | Opens specified connection. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **SetTimeout** *(+1 overloads)* | void | Sets timeout to the specified command. |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

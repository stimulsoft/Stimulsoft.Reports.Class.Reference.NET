---
title: "StiMySqlDevartConnector Class"
---

## StiMySqlDevartConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiMySqlDevartConnector
```

### Inheritance

Inherits from: [StiMySqlConnector](StiMySqlConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMySqlDevartConnector**(string connectionString) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **GetNetType** | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

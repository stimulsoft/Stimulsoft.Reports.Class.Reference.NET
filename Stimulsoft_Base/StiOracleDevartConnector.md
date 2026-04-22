---
title: "StiOracleDevartConnector Class"
---

## StiOracleDevartConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiOracleDevartConnector
```

### Inheritance

Inherits from: [StiOracleConnector](StiOracleConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiOracleDevartConnector(string connectionString)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |

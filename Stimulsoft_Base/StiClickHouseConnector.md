---
title: "StiClickHouseConnector Class"
---

## StiClickHouseConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiClickHouseConnector
```

### Inheritance

Inherits from: [StiSqlDataConnector](StiSqlDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClickHouseConnector**(string connectionString) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NuGetPackages** | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateAdapter** | DbDataAdapter |  |
| **CreateCommand** | DbCommand |  |
| **CreateParameter** *(+1 overloads)* | DbParameter |  |
| **GetDatabaseSpecificName** | string |  |
| **GetNetType** *(+1 overloads)* | Type |  |
| **GetSampleConnectionString** | string |  |
| **GetSqlType** | int |  |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) |  |

---
title: "StiSnowflakeSource Class"
---

## StiSnowflakeSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiSnowflakeSource
```

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSnowflakeSource**() |  |
| **StiSnowflakeSource**(string nameInSource, string name) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout) |  |
| **StiSnowflakeSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) |  |
| **GetDataAdapterType** | Type |  |

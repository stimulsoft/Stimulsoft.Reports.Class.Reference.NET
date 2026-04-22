---
title: "StiClickHouseSource Class"
---

## StiClickHouseSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiClickHouseSource
```

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiClickHouseSource**() |  |
| **StiClickHouseSource**(string nameInSource, string name) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout) |  |
| **StiClickHouseSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) |  |
| **GetDataAdapterType** | Type |  |

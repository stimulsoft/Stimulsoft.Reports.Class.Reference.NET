---
title: "StiOdbcSource Class"
---

## StiOdbcSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiOdbcSource
```

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOdbcSource**() |  |
| **StiOdbcSource**(string nameInSource, string name) |  |
| **StiOdbcSource**(string nameInSource, string name, string alias) |  |
| **StiOdbcSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiOdbcSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

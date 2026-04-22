---
title: "StiMSAccessSource Class"
---

## StiMSAccessSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiMSAccessSource
```

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMSAccessSource**() |  |
| **StiMSAccessSource**(string nameInSource, string name) |  |
| **StiMSAccessSource**(string nameInSource, string name, string alias) |  |
| **StiMSAccessSource**(string nameInSource, string name, string alias, string sqlCommand) |  |
| **StiMSAccessSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

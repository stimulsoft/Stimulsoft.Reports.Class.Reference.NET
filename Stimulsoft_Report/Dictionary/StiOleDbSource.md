---
title: "StiOleDbSource Class"
---

## StiOleDbSource Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiOleDbSource
```

### Inheritance

Inherits from: [StiSqlSource](StiSqlSource.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiOleDbSource**() | Creates a new object of the type StiDataViewSource. |
| **StiOleDbSource**(string nameInSource, string name) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias, string sqlCommand) | Creates a new object of the type StiOleDbSource. |
| **StiOleDbSource**(string nameInSource, string name, string alias, string sqlCommand, bool connectOnStart, bool reconnectOnEachRow, int commandTimeout, string key) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateConnector** | [StiSqlDataConnector](../../Stimulsoft_Base/StiSqlDataConnector.md) | Returns new data connector for this datasource. |
| **GetDataAdapterType** | Type |  |

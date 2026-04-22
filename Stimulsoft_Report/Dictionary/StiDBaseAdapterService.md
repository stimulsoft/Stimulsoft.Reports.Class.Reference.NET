---
title: "StiDBaseAdapterService Class"
---

## StiDBaseAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the adapter for access to dBase files.

```csharp
public class StiDBaseAdapterService
```

### Inheritance

Inherits from: [StiFileAdapterService](StiFileAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **CreateConnector** | [StiFileDataConnector](../../Stimulsoft_Base/StiFileDataConnector.md) | Returns new data connector for this type of the database. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataSourceType** | Type | Returns the type of the Data Source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |

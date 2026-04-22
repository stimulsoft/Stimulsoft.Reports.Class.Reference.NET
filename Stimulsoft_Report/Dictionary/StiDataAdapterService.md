---
title: "StiDataAdapterService Class"
---

## StiDataAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public abstract class StiDataAdapterService
```

### Inheritance

Inherits from: [StiService](../../Stimulsoft_Base/Services/StiService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectDataSourceToData** | void |  |
| **Create** *(+1 overloads)* | StiDataSource | Creates a new Data Source and adds it to the dictionary. |
| **Edit** | bool | Calls the form for data source edition. |
| **GetColumnsFromData** *(+1 overloads)* | StiDataColumnsCollection | Returns a collection of columns of data. |
| **GetDataAdapter** `static` *(+1 overloads)* | [StiDataAdapterService](StiDataAdapterService.md) | Returns adapter for Data Source. |
| **GetDataCategoryName** | string | Returns name of category for data. |
| **GetDataSourceType** | Type | Returns the type of the data source. |
| **GetDataTypes** | Type[] | Returns the array of data types to which the Data Source may refer. |
| **GetMetadataProvider** | object |  |
| **GetParametersFromData** | StiDataParametersCollection | Returns a collection of parameters of data. |
| **GetSyntaxProvider** | object |  |
| **IsAdapterDataType** | bool | Returns true if the specified type is supported by this data adapters. |
| **New** | bool | Calls the form for a new data source edition. |
| **SetDataSourceNames** | void | Fills a name and alias of the data source relying on data. |
| **ToString** | string |  |

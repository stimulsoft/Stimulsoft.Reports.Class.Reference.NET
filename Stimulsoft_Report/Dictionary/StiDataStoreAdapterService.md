---
title: "StiDataStoreAdapterService Class"
---

## StiDataStoreAdapterService Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

Describes the base adapter of data for access to data in the store.

```csharp
public abstract class StiDataStoreAdapterService
```

### Inheritance

Inherits from: [StiDataAdapterService](StiDataAdapterService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** | StiDataSource | Creates a new Data Source and adds it to the dictionary. |
| **Edit** | bool | Calls the form for Data Source edition. |
| **New** | bool | Calls the form for a new Data Source edition. |
| **SetDataSourceNames** | void | Fills a name and alias of the Data Source relying on data. |

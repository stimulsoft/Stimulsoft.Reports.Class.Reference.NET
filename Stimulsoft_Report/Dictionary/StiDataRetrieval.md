---
title: "StiDataRetrieval Class"
---

## StiDataRetrieval Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

The service allows to find all data sources, columns, relations, which are used in the report.

```csharp
public class StiDataRetrieval
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **UsedColumns** | Hashtable | Gets columns to use. |
| **UsedDataSources** | Hashtable | Gets Data Sources used. |
| **UsedRelations** | Hashtable | Gets relations to use. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Build** | void | Processes a dictionary. |
| **Dispose** | void |  |
| **Retrieval** | void | Builds hashtables with elements being used. |

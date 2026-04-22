---
title: "StiAppsRecordsCache Class"
---

## StiAppsRecordsCache Class

**Namespace:** `Stimulsoft.Base.AppsDatabase`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiAppsRecordsCache
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAppsRecordsCache**([IStiAppDatabaseConnector](../Server/IStiAppDatabaseConnector.md) dataSource, string cloudTableKey) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColumnDetails** | StiAppDatabaseColumnSizes.TableDetails |  |
| **Cursor** | [StiAppsRecord](StiAppsRecord.md) |  |
| **IsInit** | bool |  |
| **Position** | int |  |
| **TotalCount** | long |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddEmptyRowToTheEnd** | void |  |
| **AddPageToQuery** *(+1 overloads)* | void |  |
| **DeleteColumn** | void |  |
| **DeleteRows** | void |  |
| **FetchColumnsAsync** | Task |  |
| **FullClear** | void |  |
| **GetLoadingPage** | int? |  |
| **GetRecordByGridRowNumber** | [StiAppsRecord](StiAppsRecord.md) |  |
| **GetRecordByIndex** | [StiAppsRecord](StiAppsRecord.md) |  |
| **InsertColumnToTheLeft** | void |  |
| **InsertColumnToTheRight** | void |  |
| **InsertNewDefaultValueInRows** | void |  |
| **InsertRow** | void |  |
| **MoveRecordDown** | void |  |
| **MoveRecordUp** | void |  |
| **RemoveValueByColumnIndex** | void |  |
| **Save** | void |  |
| **SetNewCursor** | void |  |
| **SetSort** *(+1 overloads)* | void |  |
| **UpdateColumn** | void |  |
| **UpdateValue** | void |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ColumnCreated** | Action<[StiAppsColumnEx](StiAppsColumnEx.md)> |  |
| **ColumnDeleted** | Action<string> |  |
| **CursorChange** | Action |  |
| **GetCurrentPage** | StiGetCurrentPageAppsEventHandler |  |
| **HideLabelFetchingData** | EventHandler |  |
| **InitColumns** | Action<List<[StiAppsColumnEx](StiAppsColumnEx.md)>> |  |
| **InvalidateData** | EventHandler |  |
| **ShowLabelFetchingData** | EventHandler |  |
| **SortChanged** | Action |  |
| **TotalChanged** | EventHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SignalRConnectionId** | string |  |
| **SortRoles** | List<[StiAppsColumnSortRule](StiAppsColumnSortRule.md)> |  |

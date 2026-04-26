---
title: "StiAppsRecordsCache Class"
---

## StiAppsRecordsCache Class

**Namespace:** `Stimulsoft.Base.AppsDatabase`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAppsRecordsCache**([IStiAppDatabaseConnector](../Server/IStiAppDatabaseConnector.md) dataSource, string cloudTableKey) |  |

**StiAppsRecordsCache**(**dataSource**: [IStiAppDatabaseConnector](../Server/IStiAppDatabaseConnector.md), **cloudTableKey**: string)

**Parameters**

- **dataSource** ([IStiAppDatabaseConnector](../Server/IStiAppDatabaseConnector.md))  
- **cloudTableKey** (string)  


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

---

### Method Details

#### AddEmptyRowToTheEnd

**AddEmptyRowToTheEnd**(**record**: [StiAppsRecord](StiAppsRecord.md)): void

**Parameters**

- **record** ([StiAppsRecord](StiAppsRecord.md))  


---

#### AddPageToQuery

**AddPageToQuery**(**pageIndexes**: List<int>): void

**Parameters**

- **pageIndexes** (List<int>)  

---

**AddPageToQuery**(**pageIndex**: int): void

**Parameters**

- **pageIndex** (int)  


---

#### DeleteColumn

**DeleteColumn**(**columnName**: string): void

**Parameters**

- **columnName** (string)  


---

#### DeleteRows

**DeleteRows**(**rows**: List<int>): void

**Parameters**

- **rows** (List<int>)  


---

#### FetchColumnsAsync

**FetchColumnsAsync**(**font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): Task

**Parameters**

- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

**Returns** Task


---

#### FullClear

**FullClear**(): void


---

#### GetLoadingPage

**GetLoadingPage**(): int?

**Returns** int?


---

#### GetRecordByGridRowNumber

**GetRecordByGridRowNumber**(**rowNumber**: int): [StiAppsRecord](StiAppsRecord.md)

**Parameters**

- **rowNumber** (int)  

**Returns** [StiAppsRecord](StiAppsRecord.md)


---

#### GetRecordByIndex

**GetRecordByIndex**(**index**: int): [StiAppsRecord](StiAppsRecord.md)

**Parameters**

- **index** (int)  

**Returns** [StiAppsRecord](StiAppsRecord.md)


---

#### InsertColumnToTheLeft

**InsertColumnToTheLeft**(**column**: [StiAppsColumn](StiAppsColumn.md), **columnIndex**: int): void

**Parameters**

- **column** ([StiAppsColumn](StiAppsColumn.md))  
- **columnIndex** (int)  


---

#### InsertColumnToTheRight

**InsertColumnToTheRight**(**column**: [StiAppsColumn](StiAppsColumn.md), **columnIndex**: int): void

**Parameters**

- **column** ([StiAppsColumn](StiAppsColumn.md))  
- **columnIndex** (int)  


---

#### InsertNewDefaultValueInRows

**InsertNewDefaultValueInRows**(**column**: [StiAppsColumnEx](StiAppsColumnEx.md)): void

**Parameters**

- **column** ([StiAppsColumnEx](StiAppsColumnEx.md))  


---

#### InsertRow

**InsertRow**(**record**: [StiAppsRecord](StiAppsRecord.md), **rowIndex**: int): void

**Parameters**

- **record** ([StiAppsRecord](StiAppsRecord.md))  
- **rowIndex** (int)  


---

#### MoveRecordDown

**MoveRecordDown**(**rowIndex**: int): void

**Parameters**

- **rowIndex** (int)  


---

#### MoveRecordUp

**MoveRecordUp**(**rowIndex**: int): void

**Parameters**

- **rowIndex** (int)  


---

#### RemoveValueByColumnIndex

**RemoveValueByColumnIndex**(**columnIndex**: int): void

**Parameters**

- **columnIndex** (int)  


---

#### Save

**Save**(): void


---

#### SetNewCursor

**SetNewCursor**(**rowNumber**: int): void

**Parameters**

- **rowNumber** (int)  


---

#### SetSort

**SetSort**(**sortRoles**: List<[StiAppsColumnSortRule](StiAppsColumnSortRule.md)>): void

**Parameters**

- **sortRoles** (List<[StiAppsColumnSortRule](StiAppsColumnSortRule.md)>)  

---

**SetSort**(**sortColumn**: string, **sortAscending**: bool): void

**Parameters**

- **sortColumn** (string)  
- **sortAscending** (bool)  


---

#### UpdateColumn

**UpdateColumn**(**columnName**: string, **column**: [StiAppsColumn](StiAppsColumn.md)): void

**Parameters**

- **columnName** (string)  
- **column** ([StiAppsColumn](StiAppsColumn.md))  


---

#### UpdateValue

**UpdateValue**(**record**: [StiAppsRecord](StiAppsRecord.md), **columnIndex**: int, **newValue**: object): void

**Parameters**

- **record** ([StiAppsRecord](StiAppsRecord.md))  
- **columnIndex** (int)  
- **newValue** (object)  


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

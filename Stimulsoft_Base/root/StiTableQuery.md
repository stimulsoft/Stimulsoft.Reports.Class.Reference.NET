---
title: "StiTableQuery Class"
---

## StiTableQuery Class

**Namespace:** `Stimulsoft.Base`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableQuery**([StiSqlDataConnector](StiSqlDataConnector.md) connector) |  |

**StiTableQuery**(**connector**: [StiSqlDataConnector](StiSqlDataConnector.md))

**Parameters**

- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiTableQuery](StiTableQuery.md) |  |
| **GetCallQuery** *(+1 overloads)* | string |  |
| **GetExecuteQuery** *(+1 overloads)* | string |  |
| **GetName** | string |  |
| **GetProcQuery** *(+1 overloads)* | string |  |
| **GetSelectQuery** *(+1 overloads)* | string |  |

---

### Method Details

#### Get `static`

**Get**(**connector**: [StiSqlDataConnector](StiSqlDataConnector.md)): [StiTableQuery](StiTableQuery.md)

**Parameters**

- **connector** ([StiSqlDataConnector](StiSqlDataConnector.md))  

**Returns** [StiTableQuery](StiTableQuery.md)


---

#### GetCallQuery

**GetCallQuery**(**table**: string): string

**Parameters**

- **table** (string)  

**Returns** string

---

**GetCallQuery**(**schema**: string, **table**: string): string

**Parameters**

- **schema** (string)  
- **table** (string)  

**Returns** string


---

#### GetExecuteQuery

**GetExecuteQuery**(**table**: string): string

**Parameters**

- **table** (string)  

**Returns** string

---

**GetExecuteQuery**(**schema**: string, **table**: string): string

**Parameters**

- **schema** (string)  
- **table** (string)  

**Returns** string


---

#### GetName

**GetName**(**schema**: string, **table**: string): string

**Parameters**

- **schema** (string)  
- **table** (string)  

**Returns** string


---

#### GetProcQuery

**GetProcQuery**(**table**: string): string

**Parameters**

- **table** (string)  

**Returns** string

---

**GetProcQuery**(**schema**: string, **table**: string): string

**Parameters**

- **schema** (string)  
- **table** (string)  

**Returns** string


---

#### GetSelectQuery

**GetSelectQuery**(**table**: string): string

**Parameters**

- **table** (string)  

**Returns** string

---

**GetSelectQuery**(**schema**: string, **table**: string): string

**Parameters**

- **schema** (string)  
- **table** (string)  

**Returns** string


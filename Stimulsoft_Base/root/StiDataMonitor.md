---
title: "StiDataMonitor Class"
---

## StiDataMonitor Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Enable** `static` | bool |  |
| **Index** `static` | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearRecords** `static` | void |  |
| **Close** `static` | void |  |
| **Create** `static` *(+2 overloads)* | void |  |
| **DeriveParameters** `static` | void |  |
| **ExecuteReader** `static` | void |  |
| **FetchRecords** `static` | List<Record> |  |
| **FillAdapter** `static` *(+1 overloads)* | void |  |
| **FillSchema** `static` | void |  |
| **GetSchema** `static` | void |  |
| **Open** `static` | void |  |
| **Write** `static` | void |  |

---

### Method Details

#### ClearRecords `static`

**ClearRecords**(): void


---

#### Close `static`

**Close**(**connection**: IDbConnection): void

**Parameters**

- **connection** (IDbConnection)  


---

#### Create `static`

**Create**(**command**: DbCommand, **behavior**: CommandBehavior): void

**Parameters**

- **command** (DbCommand)  
- **behavior** (CommandBehavior)  

---

**Create**(**adapter**: DbDataAdapter): void

**Parameters**

- **adapter** (DbDataAdapter)  

---

**Create**(**adapter**: IDbDataAdapter): void

**Parameters**

- **adapter** (IDbDataAdapter)  


---

#### DeriveParameters `static`

**DeriveParameters**(**command**: DbCommand): void

**Parameters**

- **command** (DbCommand)  


---

#### ExecuteReader `static`

**ExecuteReader**(**command**: DbCommand, **behavior**: CommandBehavior): void

**Parameters**

- **command** (DbCommand)  
- **behavior** (CommandBehavior)  


---

#### FetchRecords `static`

**FetchRecords**(**fromIndex**: int): List<Record>

**Parameters**

- **fromIndex** (int)  

**Returns** List<Record>


---

#### FillAdapter `static`

**FillAdapter**(**adapter**: DbDataAdapter): void

**Parameters**

- **adapter** (DbDataAdapter)  

---

**FillAdapter**(**adapter**: IDbDataAdapter): void

**Parameters**

- **adapter** (IDbDataAdapter)  


---

#### FillSchema `static`

**FillSchema**(**adapter**: DbDataAdapter): void

**Parameters**

- **adapter** (DbDataAdapter)  


---

#### GetSchema `static`

**GetSchema**(**connection**: IDbConnection, **type**: string): void

**Parameters**

- **connection** (IDbConnection)  
- **type** (string)  


---

#### Open `static`

**Open**(**connection**: IDbConnection): void

**Parameters**

- **connection** (IDbConnection)  


---

#### Write `static`

**Write**(**message**: string): void

**Parameters**

- **message** (string)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **NewMessage** | EventHandler |  |

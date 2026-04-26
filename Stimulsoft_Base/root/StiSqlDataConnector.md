---
title: "StiSqlDataConnector Class"
---

## StiSqlDataConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSqlDataConnector**(string connectionString) |  |

**StiSqlDataConnector**(**connectionString**: string)

**Parameters**

- **connectionString** (string)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ConnectionString** | string | Gets connection string to the database. |
| **DefaultSqlType** | int | Gets the default value of the data parameter. |
| **FolderAssembly** | string |  |
| **MethodDeriveParameters** | string |  |
| **NameAssembly** | string |  |
| **SqlType** | Type | Gets the type of an enumeration which describes data types. |
| **TypeCommand** | string |  |
| **TypeCommandBuilder** | string |  |
| **TypeConnection** | string |  |
| **TypeConnectionStringBuilder** | string |  |
| **TypeDataAdapter** | string |  |
| **TypeDataSourceEnumerator** | string |  |
| **TypeDbType** | string |  |
| **TypeParameter** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CloseConnection** | void | Closes specified connection. |
| **CreateAdapter** | DbDataAdapter | Returns new data adapter to this type of the database. |
| **CreateCommand** | DbCommand | Returns new data command for this type of the database. |
| **CreateCommandBuilder** | DbCommandBuilder | Returns new CommandBuilder. |
| **CreateConnection** | DbConnection | Returns new connection to this type of the database. |
| **CreateConnectionStringBuilder** | DbConnectionStringBuilder | Returns new ConnectionStringBuilder. |
| **CreateDataSourceEnumerator** | DbDataSourceEnumerator | Returns new DataSourceEnumerator. |
| **CreateParameter** *(+1 overloads)* | DbParameter | Returns new SQL parameter with specified parameter. |
| **DeriveParameters** | void | Retrieves SQL parameters for the specified command. |
| **ExecuteNonQuery** | void |  |
| **ExecuteReader** | DbDataReader |  |
| **FillAdapter** *(+1 overloads)* | void |  |
| **FillSchemaAdapter** | void |  |
| **Get** `static` | [StiSqlDataConnector](StiSqlDataConnector.md) |  |
| **GetDataTable** | DataTable |  |
| **GetDatabaseSpecificName** | string | Bracketing string with specials characters |
| **GetDbType** | Type | Returns the type of the DBType. |
| **GetNetType** *(+1 overloads)* | Type | Returns a .NET type from the specified string representaion of the database type. |
| **GetParametersTable** | DataTable |  |
| **GetRelationsTable** | DataTable |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **GetSchema** | DataTable |  |
| **GetSchemaTable** | DataTable |  |
| **GetSqlType** | int | Returns a SQL based type from the .NET type. |
| **OpenConnection** | void | Opens specified connection. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **SetTimeout** *(+1 overloads)* | void | Sets timeout to the specified command. |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

---

### Method Details

#### CloseConnection

**CloseConnection**(**connection**: DbConnection): void

Closes specified connection.

**Parameters**

- **connection** (DbConnection)  


---

#### CreateAdapter

**CreateAdapter**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbDataAdapter

Returns new data adapter to this type of the database.

**Parameters**

- **query** (string) — A SQL query.  
- **connection** (DbConnection) — A connection to database.  
- **commandType** (CommandType) — A type of the query.  

**Returns** DbDataAdapter — Created adapter.


---

#### CreateCommand

**CreateCommand**(**query**: string, **connection**: DbConnection, **commandType**: CommandType): DbCommand

Returns new data command for this type of the database.

**Parameters**

- **query** (string) — A SQL query.  
- **connection** (DbConnection) — A connection to database.  
- **commandType** (CommandType) — A type of the command.  

**Returns** DbCommand — Created command.


---

#### CreateCommandBuilder

**CreateCommandBuilder**(): DbCommandBuilder

Returns new CommandBuilder.

**Returns** DbCommandBuilder


---

#### CreateConnection

**CreateConnection**(): DbConnection

Returns new connection to this type of the database.

**Returns** DbConnection — Created connection.


---

#### CreateConnectionStringBuilder

**CreateConnectionStringBuilder**(): DbConnectionStringBuilder

Returns new ConnectionStringBuilder.

**Returns** DbConnectionStringBuilder


---

#### CreateDataSourceEnumerator

**CreateDataSourceEnumerator**(): DbDataSourceEnumerator

Returns new DataSourceEnumerator.

**Returns** DbDataSourceEnumerator


---

#### CreateParameter

**CreateParameter**(**parameterName**: string, **value**: object, **size**: int): DbParameter

Returns new SQL parameter with specified parameter.

**Parameters**

- **parameterName** (string)  
- **value** (object)  
- **size** (int)  

**Returns** DbParameter

---

**CreateParameter**(**parameterName**: string, **type**: int, **size**: int): DbParameter

Returns new SQL parameter with specified parameter.

**Parameters**

- **parameterName** (string)  
- **type** (int)  
- **size** (int)  

**Returns** DbParameter


---

#### DeriveParameters

**DeriveParameters**(**command**: DbCommand): void

Retrieves SQL parameters for the specified command.

**Parameters**

- **command** (DbCommand)  


---

#### ExecuteNonQuery

**ExecuteNonQuery**(**command**: DbCommand): void

**Parameters**

- **command** (DbCommand)  


---

#### ExecuteReader

**ExecuteReader**(**command**: DbCommand, **behavior**: CommandBehavior): DbDataReader

**Parameters**

- **command** (DbCommand)  
- **behavior** (CommandBehavior)  

**Returns** DbDataReader


---

#### FillAdapter

**FillAdapter**(**adapter**: DbDataAdapter, **dataTable**: DataTable): void

**Parameters**

- **adapter** (DbDataAdapter)  
- **dataTable** (DataTable)  

---

**FillAdapter**(**adapter**: DbDataAdapter, **dataSet**: DataSet, **srcTable**: string): void

**Parameters**

- **adapter** (DbDataAdapter)  
- **dataSet** (DataSet)  
- **srcTable** (string)  


---

#### FillSchemaAdapter

**FillSchemaAdapter**(**adapter**: DbDataAdapter, **dataTable**: DataTable, **schemaType**: SchemaType): void

**Parameters**

- **adapter** (DbDataAdapter)  
- **dataTable** (DataTable)  
- **schemaType** (SchemaType)  


---

#### Get `static`

**Get**(**ident**: [StiConnectionIdent](StiConnectionIdent.md), **connectionString**: string): [StiSqlDataConnector](StiSqlDataConnector.md)

**Parameters**

- **ident** ([StiConnectionIdent](StiConnectionIdent.md))  
- **connectionString** (string)  

**Returns** [StiSqlDataConnector](StiSqlDataConnector.md)


---

#### GetDataTable

**GetDataTable**(**command**: DbCommand, **index**: int, **count**: int): DataTable

**Parameters**

- **command** (DbCommand)  
- **index** (int)  
- **count** (int)  

**Returns** DataTable


---

#### GetDatabaseSpecificName

**GetDatabaseSpecificName**(**name**: string): string

Bracketing string with specials characters

**Parameters**

- **name** (string) — unput string  

**Returns** string — Bracketed string


---

#### GetDbType

**GetDbType**(): Type

Returns the type of the DBType.

**Returns** Type


---

#### GetNetType

**GetNetType**(**dbType**: string): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (string)  

**Returns** Type

---

**GetNetType**(**dbType**: int): Type

Returns a .NET type from the specified int representaion of the database type.

**Parameters**

- **dbType** (int)  

**Returns** Type


---

#### GetParametersTable

**GetParametersTable**(**command**: DbCommand): DataTable

**Parameters**

- **command** (DbCommand)  

**Returns** DataTable


---

#### GetRelationsTable

**GetRelationsTable**(**connection**: DbConnection, **tableName**: string): DataTable

**Parameters**

- **connection** (DbConnection)  
- **tableName** (string)  

**Returns** DataTable


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

Returns sample of the connection string to this connector.

**Returns** string


---

#### GetSchema

**GetSchema**(**connection**: DbConnection, **type**: string, ****: stringobjs): DataTable

**Parameters**

- **connection** (DbConnection)  
- **type** (string)  
- **** (stringobjs)  

**Returns** DataTable


---

#### GetSchemaTable

**GetSchemaTable**(**command**: DbCommand, **isStoredProc**: bool): DataTable

**Parameters**

- **command** (DbCommand)  
- **isStoredProc** (bool)  

**Returns** DataTable


---

#### GetSqlType

**GetSqlType**(**type**: Type): int

Returns a SQL based type from the .NET type.

**Parameters**

- **type** (Type)  

**Returns** int


---

#### OpenConnection

**OpenConnection**(**connection**: DbConnection): void

Opens specified connection.

**Parameters**

- **connection** (DbConnection)  


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### SetTimeout

**SetTimeout**(**command**: DbCommand, **timeOut**: int): void

Sets timeout to the specified command.

**Parameters**

- **command** (DbCommand)  
- **timeOut** (int)  

---

**SetTimeout**(**command**: IDbCommand, **timeOut**: int): void

Sets timeout to the specified command.

**Parameters**

- **command** (IDbCommand)  
- **timeOut** (int)  


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct.

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md) — The result of testing the connection string.


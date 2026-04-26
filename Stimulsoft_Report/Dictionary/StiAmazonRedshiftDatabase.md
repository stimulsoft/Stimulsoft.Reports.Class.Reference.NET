---
title: "StiAmazonRedshiftDatabase Class"
---

## StiAmazonRedshiftDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiPostgreSQLDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiAmazonRedshiftDatabase**() | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string connectionString) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiAmazonRedshiftDatabase. |
| **StiAmazonRedshiftDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiAmazonRedshiftDatabase. |

**StiAmazonRedshiftDatabase**()

Creates a new object of the type StiAmazonRedshiftDatabase.

---

**StiAmazonRedshiftDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiAmazonRedshiftDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiAmazonRedshiftDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiAmazonRedshiftDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiAmazonRedshiftDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiAmazonRedshiftDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiAmazonRedshiftDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiAmazonRedshiftDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |

---

### Method Details

#### CopyDataSourceFrom

**CopyDataSourceFrom**(**dataSourceToCopy**: StiDataSource): StiDataSource

**Parameters**

- **dataSourceToCopy** (StiDataSource)  

**Returns** StiDataSource


---

#### CreateConnector

**CreateConnector**(**connectionString**: string): [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md)

Returns new data connector for this database.

**Parameters**

- **connectionString** (string)  

**Returns** [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) — Created connector.


---

#### CreateDataSource

**CreateDataSource**(**nameInSource**: string, **name**: string): [StiSqlSource](StiSqlSource.md)

Returns new data source for this database.

**Parameters**

- **nameInSource** (string)  
- **name** (string)  

**Returns** [StiSqlSource](StiSqlSource.md) — Created data source.


---

#### GetConnectionStringHelper

**GetConnectionStringHelper**(): string

**Returns** string


---

#### GetDataAdapterType

**GetDataAdapterType**(): Type

**Returns** Type


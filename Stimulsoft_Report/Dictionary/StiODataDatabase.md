---
title: "StiODataDatabase Class"
---

## StiODataDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiSqlDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataDatabase**() | Creates a new object of the type StiODataDatabase. |
| **StiODataDatabase**(string name, string connectionString) | Creates a new object of the type StiODataDatabase. |
| **StiODataDatabase**(string name, string alias, string connectionString) | Creates a new object of the type StiODataDatabase. |
| **StiODataDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword) | Creates a new object of the type StiODataDatabase. |
| **StiODataDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key) | Creates a new object of the type StiODataDatabase. |
| **StiODataDatabase**(string name, string alias, string connectionString, bool promptUserNameAndpassword, string key, [StiODataVersion](../../Stimulsoft_Base/root/StiODataVersion.md) version) | Creates a new object of the type StiODataDatabase. |

**StiODataDatabase**()

Creates a new object of the type StiODataDatabase.

---

**StiODataDatabase**(**name**: string, **connectionString**: string)

Creates a new object of the type StiODataDatabase.

**Parameters**

- **name** (string)  
- **connectionString** (string)  

---

**StiODataDatabase**(**name**: string, **alias**: string, **connectionString**: string)

Creates a new object of the type StiODataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  

---

**StiODataDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool)

Creates a new object of the type StiODataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  

---

**StiODataDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string)

Creates a new object of the type StiODataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  

---

**StiODataDatabase**(**name**: string, **alias**: string, **connectionString**: string, **promptUserNameAndpassword**: bool, **key**: string, **version**: [StiODataVersion](../../Stimulsoft_Base/root/StiODataVersion.md))

Creates a new object of the type StiODataDatabase.

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connectionString** (string)  
- **promptUserNameAndpassword** (bool)  
- **key** (string)  
- **version** ([StiODataVersion](../../Stimulsoft_Base/root/StiODataVersion.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CookieContainer** | CookieContainer |  |
| **Headers** | NameValueCollection |  |
| **Version** | [StiODataVersion](../../Stimulsoft_Base/root/StiODataVersion.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** | void |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) | Returns new data connector for this database. |
| **CreateDataSource** | [StiSqlSource](StiSqlSource.md) | Returns new data source for this database. |
| **GetConnectionStringHelper** | string |  |
| **GetDataAdapterType** | Type |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) | Returns full database information. |
| **LoadFromJsonObject** | void |  |
| **MapUserNameAndPassword** | string |  |
| **RegData** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyDatabaseInformation

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  


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


---

#### GetDatabaseInformation

**GetDatabaseInformation**(**report**: [StiReport](../root/StiReport.md)): [StiDatabaseInformation](StiDatabaseInformation.md)

Returns full database information.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiDatabaseInformation](StiDatabaseInformation.md)


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### MapUserNameAndPassword

**MapUserNameAndPassword**(**userName**: string, **password**: string): string

**Parameters**

- **userName** (string)  
- **password** (string)  

**Returns** string


---

#### RegData

**RegData**(**dictionary**: StiDictionary, **loadData**: bool): void

**Parameters**

- **dictionary** (StiDictionary)  
- **loadData** (bool)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


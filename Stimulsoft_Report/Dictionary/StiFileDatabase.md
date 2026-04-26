---
title: "StiFileDatabase Class"
---

## StiFileDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: StiDatabase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiFileDatabase**() |  |
| **StiFileDatabase**(string name, string pathData) |  |
| **StiFileDatabase**(string name, string pathData, string key) |  |
| **StiFileDatabase**(string name, string pathData, string key, [StiColumnTypeProcessing](StiColumnTypeProcessing.md) castToColumnType) |  |

**StiFileDatabase**()

---

**StiFileDatabase**(**name**: string, **pathData**: string)

**Parameters**

- **name** (string)  
- **pathData** (string)  

---

**StiFileDatabase**(**name**: string, **pathData**: string, **key**: string)

**Parameters**

- **name** (string)  
- **pathData** (string)  
- **key** (string)  

---

**StiFileDatabase**(**name**: string, **pathData**: string, **key**: string, **castToColumnType**: [StiColumnTypeProcessing](StiColumnTypeProcessing.md))

**Parameters**

- **name** (string)  
- **pathData** (string)  
- **key** (string)  
- **castToColumnType** ([StiColumnTypeProcessing](StiColumnTypeProcessing.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PathData** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyDatabaseInformation** *(+1 overloads)* | void | Adds tables, views and stored procedures to report dictionary from database information. |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateDataSources** | void |  |
| **CreateDataSourcesAsync** | Task |  |
| **CreateFileConnector** | [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) | Returns new file connector for this database. |
| **FetchSiblingDataSources** | IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)> |  |
| **GetConnectorOptions** | [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md) |  |
| **GetDatabaseInformation** | [StiDatabaseInformation](StiDatabaseInformation.md) | Returns full database information. |
| **LoadFromJsonObject** | void |  |
| **ParsePath** | string |  |
| **RegData** *(+1 overloads)* | void | Registers the database in dictionary. |
| **RegDataSetInDataStore** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ApplyDatabaseInformation

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md), **informationAll**: [StiDatabaseInformation](StiDatabaseInformation.md)): void

Adds tables, views and stored procedures to report dictionary from database information.

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **informationAll** ([StiDatabaseInformation](StiDatabaseInformation.md))  

---

**ApplyDatabaseInformation**(**information**: [StiDatabaseInformation](StiDatabaseInformation.md), **report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **information** ([StiDatabaseInformation](StiDatabaseInformation.md))  
- **report** ([StiReport](../root/StiReport.md))  


---

#### CopyDataSourceFrom

**CopyDataSourceFrom**(**dataSourceToCopy**: StiDataSource): StiDataSource

**Parameters**

- **dataSourceToCopy** (StiDataSource)  

**Returns** StiDataSource


---

#### CreateDataSources

**CreateDataSources**(**dictionary**: StiDictionary): void

**Parameters**

- **dictionary** (StiDictionary)  


---

#### CreateDataSourcesAsync

**CreateDataSourcesAsync**(**dictionary**: StiDictionary): Task

**Parameters**

- **dictionary** (StiDictionary)  

**Returns** Task


---

#### CreateFileConnector

**CreateFileConnector**(): [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md)

Returns new file connector for this database.

**Returns** [StiFileDataConnector](../../Stimulsoft_Base/root/StiFileDataConnector.md) — Created connector.


---

#### FetchSiblingDataSources

**FetchSiblingDataSources**(**dictionary**: [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md)): IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>

**Parameters**

- **dictionary** ([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md))  

**Returns** IEnumerable<[IStiAppDataSource](../../Stimulsoft_Base/root/IStiAppDataSource.md)>


---

#### GetConnectorOptions

**GetConnectorOptions**(**report**: [StiReport](../root/StiReport.md)): [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)


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

#### ParsePath

**ParsePath**(**path**: string, **report**: [StiReport](../root/StiReport.md)): string

**Parameters**

- **path** (string)  
- **report** ([StiReport](../root/StiReport.md))  

**Returns** string


---

#### RegData

**RegData**(**dictionary**: StiDictionary, **loadData**: bool): void

Registers the database in dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which is registered database.  
- **loadData** (bool) — Load the data or no.  

---

**RegData**(**dictionary**: StiDictionary, **loadData**: bool, **dataSource**: StiDataSource): void

Registers the database in dictionary.

**Parameters**

- **dictionary** (StiDictionary) — Dictionary in which is registered database.  
- **loadData** (bool) — Load the data or no.  
- **dataSource** (StiDataSource) — Data Source  


---

#### RegDataSetInDataStore

**RegDataSetInDataStore**(**dictionary**: StiDictionary, **dataSet**: DataSet, **inDataSource**: StiDataSource): void

**Parameters**

- **dictionary** (StiDictionary)  
- **dataSet** (DataSet)  
- **inDataSource** (StiDataSource)  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


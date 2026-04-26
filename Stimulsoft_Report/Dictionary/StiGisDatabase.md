---
title: "StiGisDatabase Class"
---

## StiGisDatabase Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: [StiFileDatabase](StiFileDatabase.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisDatabase**() |  |
| **StiGisDatabase**(string name, string pathData) |  |
| **StiGisDatabase**(string name, string pathData, string key) |  |
| **StiGisDatabase**(string name, string pathData, string key, [StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md) dataType) |  |
| **StiGisDatabase**(string name, string pathData, string key, [StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md) dataType, [StiColumnTypeProcessing](StiColumnTypeProcessing.md) castToColumnType) |  |

**StiGisDatabase**()

---

**StiGisDatabase**(**name**: string, **pathData**: string)

**Parameters**

- **name** (string)  
- **pathData** (string)  

---

**StiGisDatabase**(**name**: string, **pathData**: string, **key**: string)

**Parameters**

- **name** (string)  
- **pathData** (string)  
- **key** (string)  

---

**StiGisDatabase**(**name**: string, **pathData**: string, **key**: string, **dataType**: [StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md))

**Parameters**

- **name** (string)  
- **pathData** (string)  
- **key** (string)  
- **dataType** ([StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md))  

---

**StiGisDatabase**(**name**: string, **pathData**: string, **key**: string, **dataType**: [StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md), **castToColumnType**: [StiColumnTypeProcessing](StiColumnTypeProcessing.md))

**Parameters**

- **name** (string)  
- **pathData** (string)  
- **key** (string)  
- **dataType** ([StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md))  
- **castToColumnType** ([StiColumnTypeProcessing](StiColumnTypeProcessing.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DataType** | [StiGisDataType](../../Stimulsoft_Base/root/StiGisDataType.md) |  |
| **Separator** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CopyDataSourceFrom** | StiDataSource |  |
| **CreateConnector** | [StiDataConnector](../../Stimulsoft_Base/root/StiDataConnector.md) | Returns new data connector for this database. |
| **Edit** | DialogResult |  |
| **EditAsync** | Task<DialogResult> |  |
| **GetConnectorOptions** | [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md) |  |
| **GetNestedResources** | List<StiResource> | Returns a list of the resources which connected to this database. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

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

#### Edit

**Edit**(**dictionary**: StiDictionary, **newDatabase**: bool): DialogResult

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** DialogResult


---

#### EditAsync

**EditAsync**(**dictionary**: StiDictionary, **newDatabase**: bool): Task<DialogResult>

**Parameters**

- **dictionary** (StiDictionary)  
- **newDatabase** (bool)  

**Returns** Task<DialogResult>


---

#### GetConnectorOptions

**GetConnectorOptions**(**report**: [StiReport](../root/StiReport.md)): [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** [StiFileDataOptions](../../Stimulsoft_Base/root/StiFileDataOptions.md)


---

#### GetNestedResources

**GetNestedResources**(**report**: [StiReport](../root/StiReport.md)): List<StiResource>

Returns a list of the resources which connected to this database.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  

**Returns** List<StiResource> — A list of the connected to this database resources.


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---
title: "StiGoogleSheetsConnector Class"
---

## StiGoogleSheetsConnector Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Google`

### Inheritance

Inherits from: [StiDataConnector](../../../root/StiDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGoogleSheetsConnector**() |  |

**StiGoogleSheetsConnector**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ApiKey** | string |  |
| **ClientId** | string |  |
| **ClientSecret** | string |  |
| **FirstRowIsHeader** | bool |  |
| **SpreadsheetId** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiGoogleSheetsConnector](StiGoogleSheetsConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)> |  |
| **GetDataTable** | DataTable |  |
| **RetrieveSchema** | [StiDataSchema](../../../root/StiDataSchema.md) |  |

---

### Method Details

#### Get `static`

**Get**(**clientId**: string, **clientSecret**: string, **spreadsheetId**: string, **firstRowIsHeader**: bool, **apiKey**: string): [StiGoogleSheetsConnector](StiGoogleSheetsConnector.md)

**Parameters**

- **clientId** (string)  
- **clientSecret** (string)  
- **spreadsheetId** (string)  
- **firstRowIsHeader** (bool)  
- **apiKey** (string)  

**Returns** [StiGoogleSheetsConnector](StiGoogleSheetsConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](../../../root/StiDataColumnSchema.md)>


---

#### GetDataTable

**GetDataTable**(**collectionName**: string, **query**: string, **index**: int?, **count**: int?): DataTable

**Parameters**

- **collectionName** (string)  
- **query** (string)  
- **index** (int?)  
- **count** (int?)  

**Returns** DataTable


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](../../../root/StiDataSchema.md)

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](../../../root/StiDataSchema.md)


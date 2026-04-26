---
title: "StiODataConnector Class"
---

## StiODataConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiRestDataConnector](StiRestDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataConnector**(string connectionString, NameValueCollection headers) |  |

**StiODataConnector**(**connectionString**: string, **headers**: NameValueCollection)

**Parameters**

- **connectionString** (string)  
- **headers** (NameValueCollection)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowException** | bool |  |
| **CookieContainer** | CookieContainer |  |
| **Headers** | NameValueCollection | List of headers used for http requests to load data. |
| **Version** | [StiODataVersion](StiODataVersion.md) | Get or sets value, which indicates Odata version. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillDataTable** | void |  |
| **Get** `static` | [StiODataConnector](StiODataConnector.md) |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetSampleConnectionString** | string | Returns sample of the connection string to this connector. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

---

### Method Details

#### FillDataTable

**FillDataTable**(**table**: DataTable, **query**: string): void

**Parameters**

- **table** (DataTable)  
- **query** (string)  


---

#### Get `static`

**Get**(**connectionString**: string, **headers**: NameValueCollection): [StiODataConnector](StiODataConnector.md)

**Parameters**

- **connectionString** (string)  
- **headers** (NameValueCollection)  

**Returns** [StiODataConnector](StiODataConnector.md)


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


---

#### GetSampleConnectionString

**GetSampleConnectionString**(): string

Returns sample of the connection string to this connector.

**Returns** string


---

#### RetrieveSchema

**RetrieveSchema**(**allowException**: bool): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **allowException** (bool)  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct.

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md) — The result of testing the connection string.


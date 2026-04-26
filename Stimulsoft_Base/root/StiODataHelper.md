---
title: "StiODataHelper Class"
---

## StiODataHelper Class

**Namespace:** `Stimulsoft.Base`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataHelper**(string connectionString, NameValueCollection headers) |  |

**StiODataHelper**(**connectionString**: string, **headers**: NameValueCollection)

**Parameters**

- **connectionString** (string)  
- **headers** (NameValueCollection)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowException** | bool |  |
| **ConnectionString** | string |  |
| **Headers** | NameValueCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillDataTable** | void |  |
| **GetBearerAccessToken** `static` | string |  |
| **GetColumns** | List<[StiDataColumnSchema](StiDataColumnSchema.md)> |  |
| **GetNetType** `static` | Type | Returns a .NET type from the specified string representaion of the database type. |
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

#### GetBearerAccessToken `static`

**GetBearerAccessToken**(**url**: string, **userName**: string, **password**: string, **clientId**: string): string

**Parameters**

- **url** (string)  
- **userName** (string)  
- **password** (string)  
- **clientId** (string)  

**Returns** string


---

#### GetColumns

**GetColumns**(**collectionName**: string): List<[StiDataColumnSchema](StiDataColumnSchema.md)>

**Parameters**

- **collectionName** (string)  

**Returns** List<[StiDataColumnSchema](StiDataColumnSchema.md)>


---

#### GetNetType `static`

**GetNetType**(**dbType**: string): Type

Returns a .NET type from the specified string representaion of the database type.

**Parameters**

- **dbType** (string)  

**Returns** Type


---

#### RetrieveSchema

**RetrieveSchema**(): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(): [StiTestConnectionResult](StiTestConnectionResult.md)

Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct.

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md) — The result of testing the connection string.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AddressBearer** | string |  |
| **ClientId** | string |  |
| **Password** | string |  |
| **Token** | string |  |
| **UserName** | string |  |

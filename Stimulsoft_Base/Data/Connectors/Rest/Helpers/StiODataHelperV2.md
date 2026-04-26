---
title: "StiODataHelperV2 Class"
---

## StiODataHelperV2 Class

**Namespace:** `Stimulsoft.Base.Data.Connectors.Rest.Helpers`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataHelperV2**(string connectionString, string nuGetVersion, CookieContainer cookieContainer, NameValueCollection headers) |  |

**StiODataHelperV2**(**connectionString**: string, **nuGetVersion**: string, **cookieContainer**: CookieContainer, **headers**: NameValueCollection)

**Parameters**

- **connectionString** (string)  
- **nuGetVersion** (string)  
- **cookieContainer** (CookieContainer)  
- **headers** (NameValueCollection)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowException** | bool |  |
| **ConnectionString** | string |  |
| **CookieContainer** | CookieContainer |  |
| **Headers** | NameValueCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillDataTable** | void |  |
| **GetColumns** | List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)> |  |
| **RetrieveSchema** | [StiDataSchema](../../../../root/StiDataSchema.md) |  |

---

### Method Details

#### FillDataTable

**FillDataTable**(**table**: DataTable, **query**: string): void

**Parameters**

- **table** (DataTable)  
- **query** (string)  


---

#### GetColumns

**GetColumns**(**tableName**: string): List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>

**Parameters**

- **tableName** (string)  

**Returns** List<[StiDataColumnSchema](../../../../root/StiDataColumnSchema.md)>


---

#### RetrieveSchema

**RetrieveSchema**(): [StiDataSchema](../../../../root/StiDataSchema.md)

**Returns** [StiDataSchema](../../../../root/StiDataSchema.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AddressBearer** | string |  |
| **ClientId** | string |  |
| **Password** | string |  |
| **Token** | string |  |
| **UserName** | string |  |

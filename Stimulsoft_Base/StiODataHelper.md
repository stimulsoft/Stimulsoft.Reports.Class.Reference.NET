---
title: "StiODataHelper Class"
---

## StiODataHelper Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiODataHelper
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataHelper**(string connectionString, NameValueCollection headers) |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AddressBearer** | string |  |
| **ClientId** | string |  |
| **Password** | string |  |
| **Token** | string |  |
| **UserName** | string |  |

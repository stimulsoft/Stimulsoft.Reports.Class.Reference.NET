---
title: "StiODataConnector Class"
---

## StiODataConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiODataConnector
```

### Inheritance

Inherits from: [StiRestDataConnector](StiRestDataConnector.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiODataConnector**(string connectionString, NameValueCollection headers) |  |

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

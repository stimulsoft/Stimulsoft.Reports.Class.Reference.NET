---
title: "StiFunctionsData Class"
---

## StiFunctionsData Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiFunctionsData
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Coalesce** `static` | object | Returns the first non-null and non-DBNull value from the provided arguments. |
| **CoalesceStr** `static` | string | Returns the first non-null and non-empty string from the provided arguments. |
| **GetCrossTabColumnValue** `static` | string | Retrieves the cross-tab column value from the provided sender object. |
| **GetCrossTabRowValue** `static` | string | Retrieves the cross-tab row value from the provided sender object. |
| **GetRealPageNumber** `static` | int | Retrieves the real page number from the provided sender object. |
| **IsAllDataRowNullOrEmpty** `static` | bool | Checks if all rows in the specified data column of the given data source or business object are null or empty. |
| **IsDataEmpty** `static` | bool | Checks if the specified data source or business object is empty. |
| **IsNull** `static` | bool | Determines whether the specified data column in the given data source or business object is null. |
| **IsNullOrEmpty** `static` *(+1 overloads)* | bool | Determines whether the specified data column in the given data source or business object is null or empty. |
| **IsNullOrWhiteSpace** `static` *(+1 overloads)* | bool | Determines whether the specified data column in the given data source or business object is null or consists only of white-space characters. |
| **IsNumeric** `static` | bool | Determines whether the specified value is numeric. |
| **JoinColumnContent** `static` | string | Joins the content of a specified column from a data source or business object into a single string, separated by a specified delimiter. |
| **Next** `static` | object | Retrieves the value of the specified data column from the next row in the given data source or business object. |
| **NextIsNull** `static` | bool | Determines whether the next row's specified data column in the given data source or business object is null. |
| **Previous** `static` | object | Retrieves the value of the specified data column from the previous row in the given data source or business object. |
| **PreviousIsNull** `static` | bool | Determines whether the previous row's specified data column in the given data source or business object is null. |
| **ToQueryString** `static` | string | Converts a list of items to a query string format. |
| **VLookup** `static` | object | Performs a vertical lookup for a specified value in a data source or business object. |
| **VLookupStr** `static` | object | Performs a vertical lookup for a specified value in a data source or business object, with an option for exact match. |

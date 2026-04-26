---
title: "StiFunctionsData Class"
---

## StiFunctionsData Class

**Namespace:** `Stimulsoft.Report.Dictionary`

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

---

### Method Details

#### Coalesce `static`

**Coalesce**(****: objectargs): object

Returns the first non-null and non-DBNull value from the provided arguments.

**Parameters**

- **** (objectargs)  

**Returns** object — The first non-null and non-DBNull value, or null if all arguments are null or DBNull.


---

#### CoalesceStr `static`

**CoalesceStr**(****: objectargs): string

Returns the first non-null and non-empty string from the provided arguments.

**Parameters**

- **** (objectargs)  

**Returns** string — The first non-null and non-empty string, or null if all arguments are null or empty.


---

#### GetCrossTabColumnValue `static`

**GetCrossTabColumnValue**(**sender**: object): string

Retrieves the cross-tab column value from the provided sender object.

**Parameters**

- **sender** (object) — The sender object, expected to be of type StiCrossSummary.  

**Returns** string — The cross-tab column value as a string, or null if the sender is not of the expected type.


---

#### GetCrossTabRowValue `static`

**GetCrossTabRowValue**(**sender**: object): string

Retrieves the cross-tab row value from the provided sender object.

**Parameters**

- **sender** (object) — The sender object, expected to be of type StiCrossSummary.  

**Returns** string — The cross-tab row value as a string, or null if the sender is not of the expected type.


---

#### GetRealPageNumber `static`

**GetRealPageNumber**(**sender**: object): int

Retrieves the real page number from the provided sender object.

**Parameters**

- **sender** (object) — The sender object, expected to be of type object.  

**Returns** int — The real page number as an integer.


---

#### IsAllDataRowNullOrEmpty `static`

**IsAllDataRowNullOrEmpty**(**dataSource**: object, **dataColumn**: string): bool

Checks if all rows in the specified data column of the given data source or business object are null or empty.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if all rows in the specified data column are null or empty; otherwise, false.


---

#### IsDataEmpty `static`

**IsDataEmpty**(**dataSource**: object): bool

Checks if the specified data source or business object is empty.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  

**Returns** bool — True if the data source or business object is empty; otherwise, false.


---

#### IsNull `static`

**IsNull**(**dataSource**: object, **dataColumn**: string): bool

Determines whether the specified data column in the given data source or business object is null.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if the specified data column is null; otherwise, false.


---

#### IsNullOrEmpty `static`

**IsNullOrEmpty**(**dataSource**: object, **dataColumn**: string): bool

Determines whether the specified data column in the given data source or business object is null or empty.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if the specified data column is null or empty; otherwise, false.

---

**IsNullOrEmpty**(**value**: object): bool

Determines whether the specified value is null or empty.

**Parameters**

- **value** (object) — The value to check.  

**Returns** bool — True if the value is null or empty; otherwise, false.


---

#### IsNullOrWhiteSpace `static`

**IsNullOrWhiteSpace**(**dataSource**: object, **dataColumn**: string): bool

Determines whether the specified data column in the given data source or business object is null or consists only of white-space characters.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if the specified data column is null or consists only of white-space characters; otherwise, false.

---

**IsNullOrWhiteSpace**(**value**: object): bool

Determines whether the specified value is null or consists only of white-space characters.

**Parameters**

- **value** (object) — The value to check.  

**Returns** bool — True if the value is null or consists only of white-space characters; otherwise, false.


---

#### IsNumeric `static`

**IsNumeric**(**value**: object): bool

Determines whether the specified value is numeric.

**Parameters**

- **value** (object) — The value to check.  

**Returns** bool — True if the value is numeric; otherwise, false.


---

#### JoinColumnContent `static`

**JoinColumnContent**(**dataSource**: object, **dataColumn**: string, **delimiter**: string, **distinct**: bool): string

Joins the content of a specified column from a data source or business object into a single string, separated by a specified delimiter.

**Parameters**

- **dataSource** (object) — The data source or business object containing the column.  
- **dataColumn** (string) — The name of the column whose content is to be joined.  
- **delimiter** (string) — The delimiter to use for separating the column values in the resulting string.  
- **distinct** (bool) — Indicates whether to include only distinct values from the column.  

**Returns** string — A string containing the joined column values, separated by the specified delimiter.


---

#### Next `static`

**Next**(**dataSource**: object, **dataColumn**: string): object

Retrieves the value of the specified data column from the next row in the given data source or business object.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to retrieve the value from.  

**Returns** object — The value of the specified data column from the next row, or null if the next row does not exist.


---

#### NextIsNull `static`

**NextIsNull**(**dataSource**: object, **dataColumn**: string): bool

Determines whether the next row's specified data column in the given data source or business object is null.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if the next row's specified data column is null; otherwise, false.


---

#### Previous `static`

**Previous**(**dataSource**: object, **dataColumn**: string): object

Retrieves the value of the specified data column from the previous row in the given data source or business object.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to retrieve the value from.  

**Returns** object — The value of the specified data column from the previous row, or null if the previous row does not exist.


---

#### PreviousIsNull `static`

**PreviousIsNull**(**dataSource**: object, **dataColumn**: string): bool

Determines whether the previous row's specified data column in the given data source or business object is null.

**Parameters**

- **dataSource** (object) — The data source or business object to check.  
- **dataColumn** (string) — The name of the data column to check.  

**Returns** bool — True if the previous row's specified data column is null; otherwise, false.


---

#### ToQueryString `static`

**ToQueryString**(**list**: List<T>, **quotationMark**: string, **dateTimeFormat**: string, **needEscape**: bool): string

Converts a list of items to a query string format.

**Parameters**

- **list** (List<T>) — The list of items to convert.  
- **quotationMark** (string) — The quotation mark to use for string values.  
- **dateTimeFormat** (string) — The format to use for DateTime values.  
- **needEscape** (bool) — Indicates whether the values need to be escaped.  

**Returns** string — A query string representation of the list.


---

#### VLookup `static`

**VLookup**(**value**: object, **dataObject**: object, **dataColumnToLook**: string, **dataColumnToReturn**: string): object

Performs a vertical lookup for a specified value in a data source or business object.

**Parameters**

- **value** (object) — The value to search for in the specified data column.  
- **dataObject** (object) — The data source or business object to search within.  
- **dataColumnToLook** (string) — The name of the data column to search for the value.  
- **dataColumnToReturn** (string) — The name of the data column from which to return the value.  

**Returns** object — The value from the specified data column to return, or null if the value is not found.


---

#### VLookupStr `static`

**VLookupStr**(**value**: object, **dataObject**: object, **dataColumnToLook**: string, **dataColumnToReturn**: string, **exactMatch**: bool): object

Performs a vertical lookup for a specified value in a data source or business object, with an option for exact match.

**Parameters**

- **value** (object) — The value to search for in the specified data column.  
- **dataObject** (object) — The data source or business object to search within.  
- **dataColumnToLook** (string) — The name of the data column to search for the value.  
- **dataColumnToReturn** (string) — The name of the data column from which to return the value.  
- **exactMatch** (bool) — Indicates whether to perform an exact match search.  

**Returns** object — The value from the specified data column to return, or null if the value is not found.


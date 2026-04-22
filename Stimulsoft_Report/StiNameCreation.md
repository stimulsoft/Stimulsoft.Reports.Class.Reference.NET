---
title: "StiNameCreation Class"
---

## StiNameCreation Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

Describes the class that used for report names creation.

```csharp
public sealed class StiNameCreation
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateCategoryOfVariableName** `static` | string | Creates a category name for a variable in the report by removing spaces and ensuring uniqueness. |
| **CreateColumnName** `static` | string | Creates a column name for the data source by removing spaces and ensuring uniqueness. |
| **CreateConnectionName** `static` | string | Creates a connection name for the report by removing spaces and ensuring uniqueness. |
| **CreateDataSourcesName** `static` | string | Creates a name for the data sources in the report by removing spaces and ensuring uniqueness. |
| **CreateName** `static` *(+2 overloads)* | string | Creates a name from the base name which is correct for the report. |
| **CreateParameterName** `static` | string | Creates a parameter name for the given SQL source by removing spaces and ensuring uniqueness. |
| **CreateRelationName** `static` *(+1 overloads)* | string | Creates a relation name for the report by removing spaces and ensuring uniqueness. |
| **CreateResourceName** `static` | string | Creates a resource name for the report by removing spaces and ensuring uniqueness. |
| **CreateSimpleName** `static` | string | Creates a simple name for the report by removing spaces and adding an index. |
| **CreateUserFunctionName** `static` | string | Creates a user function name for the report by removing spaces and ensuring uniqueness. |
| **CreateVariableName** `static` | string | Creates a variable name for the report by removing spaces and ensuring uniqueness. |
| **Exists** `static` *(+1 overloads)* | bool | Checks if an object with the specified name exists in the report. |
| **GenerateName** `static` *(+4 overloads)* | string | Returns a name of the component. |
| **GetObjectWithName** `static` | object | Gets the object with the specified name in the report. |
| **IsCategoryOfVariableNameExists** `static` | bool | Checks if a category with the specified name exists in the report's variables. |
| **IsColumnNameExists** `static` | bool | Checks if a column with the specified name exists in the data source. |
| **IsConnectionNameExists** `static` | bool | Checks if a connection with the specified name exists in the report. |
| **IsParameterNameExists** `static` | bool | Checks if a parameter with the specified name exists in the SQL source. |
| **IsRelationExists** `static` | bool | Checks if a relation with the specified name exists in the report. |
| **IsResourceNameExists** `static` | bool | Checks if a resource with the specified name exists in the report. |
| **IsTableDataSourcesExists** `static` | bool | Checks if a data source with the specified name exists in the report. |
| **IsValidName** `static` | bool | Checks whether the name of the report is correct. |

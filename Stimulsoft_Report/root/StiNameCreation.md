---
title: "StiNameCreation Class"
---

## StiNameCreation Class

**Namespace:** `Stimulsoft.Report`

Describes the class that used for report names creation.

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

---

### Method Details

#### CreateCategoryOfVariableName `static`

**CreateCategoryOfVariableName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a category name for a variable in the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the category name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated category name.


---

#### CreateColumnName `static`

**CreateColumnName**(**dataSource**: StiDataSource, **baseName**: string): string

Creates a column name for the data source by removing spaces and ensuring uniqueness.

**Parameters**

- **dataSource** (StiDataSource) — The data source object for which the column name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated column name.


---

#### CreateConnectionName `static`

**CreateConnectionName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a connection name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the connection name is being created.  
- **baseName** (string) — The base name to process.  

**Returns** string — The generated connection name.


---

#### CreateDataSourcesName `static`

**CreateDataSourcesName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a name for the data sources in the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the data source name is being created.  
- **baseName** (string) — The base name to process.  

**Returns** string — The generated data source name.


---

#### CreateName `static`

**CreateName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a name from the base name which is correct for the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — Report.  
- **baseName** (string) — The type to form a name.  

**Returns** string

---

**CreateName**(**report**: [StiReport](StiReport.md), **baseName**: string, **addOne**: bool, **removeIncorrectSymbols**: bool): string

Creates a name from the base name which is correct for the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the name is being created.  
- **baseName** (string) — The base name to process.  
- **addOne** (bool) — Indicates whether to add the number one to the base name.  
- **removeIncorrectSymbols** (bool) — Indicates whether to remove incorrect symbols from the base name.  

**Returns** string — The generated name.

---

**CreateName**(**report**: [StiReport](StiReport.md), **baseName**: string, **addOne**: bool, **removeIncorrectSymbols**: bool, **forceAdvancedNamingRule**: bool): string

Creates a name from the base name which is correct for the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — Report.  
- **baseName** (string) — The type to form a name.  
- **addOne** (bool)  
- **removeIncorrectSymbols** (bool)  
- **forceAdvancedNamingRule** (bool)  

**Returns** string


---

#### CreateParameterName `static`

**CreateParameterName**(**dataSource**: [StiSqlSource](../Dictionary/StiSqlSource.md), **baseName**: string): string

Creates a parameter name for the given SQL source by removing spaces and ensuring uniqueness.

**Parameters**

- **dataSource** ([StiSqlSource](../Dictionary/StiSqlSource.md)) — The SQL source object for which the parameter name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated parameter name.


---

#### CreateRelationName `static`

**CreateRelationName**(**report**: [StiReport](StiReport.md), **dataRelation**: StiDataRelation, **baseName**: string): string

Creates a relation name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the relation name is being created.  
- **dataRelation** (StiDataRelation) — The data relation object for which the name is being created.  
- **baseName** (string) — The base name to process.  

**Returns** string — The generated relation name.

---

**CreateRelationName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a relation name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the relation name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated relation name.


---

#### CreateResourceName `static`

**CreateResourceName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a resource name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the resource name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated resource name.


---

#### CreateSimpleName `static`

**CreateSimpleName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a simple name for the report by removing spaces and adding an index.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the name is being created.  
- **baseName** (string) — The base name to process.  

**Returns** string — The generated simple name.


---

#### CreateUserFunctionName `static`

**CreateUserFunctionName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a user function name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the user function name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated user function name.


---

#### CreateVariableName `static`

**CreateVariableName**(**report**: [StiReport](StiReport.md), **baseName**: string): string

Creates a variable name for the report by removing spaces and ensuring uniqueness.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object for which the variable name is being created.  
- **baseName** (string) — The base name to process. If null, a default name is used.  

**Returns** string — The generated variable name.


---

#### Exists `static`

**Exists**(**checkedObject**: object, **report**: [StiReport](StiReport.md), **name**: string): bool

Checks if an object with the specified name exists in the report.

**Parameters**

- **checkedObject** (object) — The object to check.  
- **report** ([StiReport](StiReport.md)) — The report object to check within.  
- **name** (string) — The name to check for.  

**Returns** bool — True if an object with the specified name exists, otherwise false.

---

**Exists**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks if an object with the specified name exists in the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check within.  
- **name** (string) — The name to check for.  

**Returns** bool — True if an object with the specified name exists, otherwise false.


---

#### GenerateName `static`

**GenerateName**(**report**: [StiReport](StiReport.md), **localizedName**: string, **name**: string): string

Returns a name of the component.

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **localizedName** (string) — Localized component name.  
- **name** (string) — Did not localized component name.  

**Returns** string — Component name.

---

**GenerateName**(**report**: [StiReport](StiReport.md), **localizedName**: string, **type**: Type): string

Returns a name of the component.

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **localizedName** (string) — Localized component name.  
- **type** (Type) — Type of component.  

**Returns** string — Component name.

---

**GenerateName**(**component**: StiComponent): string

Returns a name for the component.

**Parameters**

- **component** (StiComponent) — Component for which a name is created.  

**Returns** string — Component name.

---

**GenerateName**(**relation**: StiDataRelation): string

Returns a name for the relation.

**Parameters**

- **relation** (StiDataRelation) — Relation for which a name is created.  

**Returns** string — Relation name.

---

**GenerateName**(**dataSource**: StiDataSource): string

Returns a name for the datasource.

**Parameters**

- **dataSource** (StiDataSource) — Datasource for which a name is created.  

**Returns** string — Datasource name.


---

#### GetObjectWithName `static`

**GetObjectWithName**(**checkedObject**: object, **report**: [StiReport](StiReport.md), **name**: string): object

Gets the object with the specified name in the report.

**Parameters**

- **checkedObject** (object) — The object to check.  
- **report** ([StiReport](StiReport.md)) — The report object to check within.  
- **name** (string) — The name to check for.  

**Returns** object — The object with the specified name, or null if not found.


---

#### IsCategoryOfVariableNameExists `static`

**IsCategoryOfVariableNameExists**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks if a category with the specified name exists in the report's variables.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check.  
- **name** (string) — The name of the category to check.  

**Returns** bool — True if the category exists, otherwise false.


---

#### IsColumnNameExists `static`

**IsColumnNameExists**(**dataSource**: StiDataSource, **name**: string): bool

Checks if a column with the specified name exists in the data source.

**Parameters**

- **dataSource** (StiDataSource) — The data source object to check.  
- **name** (string) — The name of the column to check.  

**Returns** bool — True if the column exists, otherwise false.


---

#### IsConnectionNameExists `static`

**IsConnectionNameExists**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks if a connection with the specified name exists in the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check.  
- **name** (string) — The name of the connection to check.  

**Returns** bool — True if the connection exists, otherwise false.


---

#### IsParameterNameExists `static`

**IsParameterNameExists**(**dataSource**: [StiSqlSource](../Dictionary/StiSqlSource.md), **name**: string): bool

Checks if a parameter with the specified name exists in the SQL source.

**Parameters**

- **dataSource** ([StiSqlSource](../Dictionary/StiSqlSource.md)) — The SQL source object to check.  
- **name** (string) — The name of the parameter to check.  

**Returns** bool — True if the parameter exists, otherwise false.


---

#### IsRelationExists `static`

**IsRelationExists**(**report**: [StiReport](StiReport.md), **dataRelation**: StiDataRelation, **name**: string): bool

Checks if a relation with the specified name exists in the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check.  
- **dataRelation** (StiDataRelation) — The data relation object to compare.  
- **name** (string) — The name of the relation to check.  

**Returns** bool — True if the relation exists, otherwise false.


---

#### IsResourceNameExists `static`

**IsResourceNameExists**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks if a resource with the specified name exists in the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check.  
- **name** (string) — The name of the resource to check.  

**Returns** bool — True if the resource exists, otherwise false.


---

#### IsTableDataSourcesExists `static`

**IsTableDataSourcesExists**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks if a data source with the specified name exists in the report.

**Parameters**

- **report** ([StiReport](StiReport.md)) — The report object to check.  
- **name** (string) — The name of the data source to check.  

**Returns** bool — True if the data source exists, otherwise false.


---

#### IsValidName `static`

**IsValidName**(**report**: [StiReport](StiReport.md), **name**: string): bool

Checks whether the name of the report is correct.

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **name** (string) — Checked name.  

**Returns** bool — Result of checking.


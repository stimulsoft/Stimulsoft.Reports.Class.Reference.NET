---
title: "StiStringsTableHelper Class"
---

## StiStringsTableHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadColumnsAndStringRowsFromCache** `static` | List<string[]> |  |
| **LoadColumnsAndStringRowsFromPackedString** `static` | List<string[]> |  |
| **LoadColumnsAndStringRowsFromString** `static` | List<string[]> |  |
| **LoadDataTableFromPackedString** `static` | DataTable |  |
| **LoadDataTableFromString** `static` | DataTable |  |
| **LoadDataTableFromStringRows** `static` | DataTable |  |
| **LoadStringRowsFromCache** `static` | List<string[]> |  |
| **LoadStringRowsFromPackedString** `static` | List<string[]> |  |
| **LoadStringRowsFromString** `static` | List<string[]> |  |
| **RemoveFromCache** `static` | void |  |
| **SaveColumnsAndStringRowsToCache** `static` | void |  |
| **SaveDataTableToCache** `static` | void |  |
| **SaveDataTableToPackedString** `static` | string |  |
| **SaveDataTableToString** `static` | string |  |
| **SaveDataTableToStringRows** `static` | List<string[]> |  |
| **SaveStringRowsToCache** `static` | void |  |

---

### Method Details

#### LoadColumnsAndStringRowsFromCache `static`

**LoadColumnsAndStringRowsFromCache**(**element**: IStiElement, ****: stringcolumns): List<string[]>

**Parameters**

- **element** (IStiElement)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### LoadColumnsAndStringRowsFromPackedString `static`

**LoadColumnsAndStringRowsFromPackedString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### LoadColumnsAndStringRowsFromString `static`

**LoadColumnsAndStringRowsFromString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### LoadDataTableFromPackedString `static`

**LoadDataTableFromPackedString**(**content**: string, ****: stringcolumns): DataTable

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** DataTable


---

#### LoadDataTableFromString `static`

**LoadDataTableFromString**(**content**: string, ****: stringcolumns): DataTable

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** DataTable


---

#### LoadDataTableFromStringRows `static`

**LoadDataTableFromStringRows**(**rows**: List<string>, ****: stringcolumns): DataTable

**Parameters**

- **rows** (List<string>)  
- **** (stringcolumns)  

**Returns** DataTable


---

#### LoadStringRowsFromCache `static`

**LoadStringRowsFromCache**(**element**: IStiElement): List<string[]>

**Parameters**

- **element** (IStiElement)  

**Returns** List<string[]>


---

#### LoadStringRowsFromPackedString `static`

**LoadStringRowsFromPackedString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### LoadStringRowsFromString `static`

**LoadStringRowsFromString**(**content**: string, ****: stringcolumns): List<string[]>

**Parameters**

- **content** (string)  
- **** (stringcolumns)  

**Returns** List<string[]>


---

#### RemoveFromCache `static`

**RemoveFromCache**(**element**: IStiElement): void

**Parameters**

- **element** (IStiElement)  


---

#### SaveColumnsAndStringRowsToCache `static`

**SaveColumnsAndStringRowsToCache**(**element**: IStiElement, ****: stringcolumns, **rows**: List<string>): void

**Parameters**

- **element** (IStiElement)  
- **** (stringcolumns)  
- **rows** (List<string>)  


---

#### SaveDataTableToCache `static`

**SaveDataTableToCache**(**element**: IStiElement, **table**: DataTable, **saveHeaders**: bool): void

**Parameters**

- **element** (IStiElement)  
- **table** (DataTable)  
- **saveHeaders** (bool)  


---

#### SaveDataTableToPackedString `static`

**SaveDataTableToPackedString**(**table**: DataTable): string

**Parameters**

- **table** (DataTable)  

**Returns** string


---

#### SaveDataTableToString `static`

**SaveDataTableToString**(**table**: DataTable): string

**Parameters**

- **table** (DataTable)  

**Returns** string


---

#### SaveDataTableToStringRows `static`

**SaveDataTableToStringRows**(**table**: DataTable, **saveHeaders**: bool): List<string[]>

**Parameters**

- **table** (DataTable)  
- **saveHeaders** (bool)  

**Returns** List<string[]>


---

#### SaveStringRowsToCache `static`

**SaveStringRowsToCache**(**element**: IStiElement, **rows**: List<string>): void

**Parameters**

- **element** (IStiElement)  
- **rows** (List<string>)  


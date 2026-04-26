---
title: "DataTableExtensions Class"
---

## DataTableExtensions Class

**Namespace:** `Stimulsoft.Base`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddColumn** `static` *(+1 overloads)* | DataTable |  |
| **AddColumns** `static` | DataTable |  |
| **Read** `static` *(+1 overloads)* | void |  |
| **ReadFrom** `static` | DataTable |  |
| **ReadFromJson** `static` | DataTable |  |
| **ReadFromString** `static` | DataTable |  |
| **WriteToArray** `static` | byte[] |  |
| **WriteToJson** `static` | string |  |
| **WriteToString** `static` *(+1 overloads)* | string |  |

---

### Method Details

#### AddColumn `static`

**AddColumn**(**table**: DataTable, **name**: string): DataTable

**Parameters**

- **table** (DataTable)  
- **name** (string)  

**Returns** DataTable

---

**AddColumn**(**table**: DataTable, **name**: string, **type**: Type): DataTable

**Parameters**

- **table** (DataTable)  
- **name** (string)  
- **type** (Type)  

**Returns** DataTable


---

#### AddColumns `static`

**AddColumns**(**table**: DataTable, ****: stringnames): DataTable

**Parameters**

- **table** (DataTable)  
- **** (stringnames)  

**Returns** DataTable


---

#### Read `static`

**Read**(**table**: DataTable, ****: bytecontent): void

**Parameters**

- **table** (DataTable)  
- **** (bytecontent)  

---

**Read**(**table**: DataTable, **content**: string): void

**Parameters**

- **table** (DataTable)  
- **content** (string)  


---

#### ReadFrom `static`

**ReadFrom**(**type**: [StiDataFormatType](StiDataFormatType.md), **str**: string): DataTable

**Parameters**

- **type** ([StiDataFormatType](StiDataFormatType.md))  
- **str** (string)  

**Returns** DataTable


---

#### ReadFromJson `static`

**ReadFromJson**(**json**: string): DataTable

**Parameters**

- **json** (string)  

**Returns** DataTable


---

#### ReadFromString `static`

**ReadFromString**(**content**: string): DataTable

**Parameters**

- **content** (string)  

**Returns** DataTable


---

#### WriteToArray `static`

**WriteToArray**(**table**: DataTable): byte[]

**Parameters**

- **table** (DataTable)  

**Returns** byte[]


---

#### WriteToJson `static`

**WriteToJson**(**table**: DataTable): string

**Parameters**

- **table** (DataTable)  

**Returns** string


---

#### WriteToString `static`

**WriteToString**(**table**: DataTable): string

**Parameters**

- **table** (DataTable)  

**Returns** string

---

**WriteToString**(**table**: DataTable, **type**: [StiDataFormatType](StiDataFormatType.md)): string

**Parameters**

- **table** (DataTable)  
- **type** ([StiDataFormatType](StiDataFormatType.md))  

**Returns** string


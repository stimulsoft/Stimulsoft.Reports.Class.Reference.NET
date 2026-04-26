---
title: "ExcelBinaryReader Class"
---

## ExcelBinaryReader Class

**Namespace:** `Stimulsoft.Base.Excel`

ExcelDataReader Class

### Inheritance

Implements: [IExcelDataReader](IExcelDataReader.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AsDataSet** *(+1 overloads)* | DataSet |  |
| **Close** | void |  |
| **Dispose** | void |  |
| **GetBoolean** | bool |  |
| **GetByte** | byte |  |
| **GetBytes** | long |  |
| **GetChar** | char |  |
| **GetChars** | long |  |
| **GetData** | IDataReader |  |
| **GetDataTypeName** | string |  |
| **GetDateTime** | DateTime |  |
| **GetDecimal** | decimal |  |
| **GetDouble** | double |  |
| **GetFieldType** | Type |  |
| **GetFloat** | float |  |
| **GetGuid** | Guid |  |
| **GetInt16** | short |  |
| **GetInt32** | int |  |
| **GetInt64** | long |  |
| **GetName** | string |  |
| **GetOrdinal** | int |  |
| **GetSchemaTable** | DataTable |  |
| **GetString** | string |  |
| **GetValue** | object |  |
| **GetValues** | int |  |
| **Initialize** | void |  |
| **IsDBNull** | bool |  |
| **NextResult** | bool |  |
| **Read** | bool |  |

---

### Method Details

#### AsDataSet

**AsDataSet**(): DataSet

**Returns** DataSet

---

**AsDataSet**(**convertOADateTime**: bool, **maxDataRows**: int): DataSet

**Parameters**

- **convertOADateTime** (bool)  
- **maxDataRows** (int)  

**Returns** DataSet


---

#### Close

**Close**(): void


---

#### Dispose

**Dispose**(): void


---

#### GetBoolean

**GetBoolean**(**i**: int): bool

**Parameters**

- **i** (int)  

**Returns** bool


---

#### GetByte

**GetByte**(**i**: int): byte

**Parameters**

- **i** (int)  

**Returns** byte


---

#### GetBytes

**GetBytes**(**i**: int, **fieldOffset**: long, ****: bytebuffer, **bufferoffset**: int, **length**: int): long

**Parameters**

- **i** (int)  
- **fieldOffset** (long)  
- **** (bytebuffer)  
- **bufferoffset** (int)  
- **length** (int)  

**Returns** long


---

#### GetChar

**GetChar**(**i**: int): char

**Parameters**

- **i** (int)  

**Returns** char


---

#### GetChars

**GetChars**(**i**: int, **fieldoffset**: long, ****: charbuffer, **bufferoffset**: int, **length**: int): long

**Parameters**

- **i** (int)  
- **fieldoffset** (long)  
- **** (charbuffer)  
- **bufferoffset** (int)  
- **length** (int)  

**Returns** long


---

#### GetData

**GetData**(**i**: int): IDataReader

**Parameters**

- **i** (int)  

**Returns** IDataReader


---

#### GetDataTypeName

**GetDataTypeName**(**i**: int): string

**Parameters**

- **i** (int)  

**Returns** string


---

#### GetDateTime

**GetDateTime**(**i**: int): DateTime

**Parameters**

- **i** (int)  

**Returns** DateTime


---

#### GetDecimal

**GetDecimal**(**i**: int): decimal

**Parameters**

- **i** (int)  

**Returns** decimal


---

#### GetDouble

**GetDouble**(**i**: int): double

**Parameters**

- **i** (int)  

**Returns** double


---

#### GetFieldType

**GetFieldType**(**i**: int): Type

**Parameters**

- **i** (int)  

**Returns** Type


---

#### GetFloat

**GetFloat**(**i**: int): float

**Parameters**

- **i** (int)  

**Returns** float


---

#### GetGuid

**GetGuid**(**i**: int): Guid

**Parameters**

- **i** (int)  

**Returns** Guid


---

#### GetInt16

**GetInt16**(**i**: int): short

**Parameters**

- **i** (int)  

**Returns** short


---

#### GetInt32

**GetInt32**(**i**: int): int

**Parameters**

- **i** (int)  

**Returns** int


---

#### GetInt64

**GetInt64**(**i**: int): long

**Parameters**

- **i** (int)  

**Returns** long


---

#### GetName

**GetName**(**i**: int): string

**Parameters**

- **i** (int)  

**Returns** string


---

#### GetOrdinal

**GetOrdinal**(**name**: string): int

**Parameters**

- **name** (string)  

**Returns** int


---

#### GetSchemaTable

**GetSchemaTable**(): DataTable

**Returns** DataTable


---

#### GetString

**GetString**(**i**: int): string

**Parameters**

- **i** (int)  

**Returns** string


---

#### GetValue

**GetValue**(**i**: int): object

**Parameters**

- **i** (int)  

**Returns** object


---

#### GetValues

**GetValues**(****: objectvalues): int

**Parameters**

- **** (objectvalues)  

**Returns** int


---

#### Initialize

**Initialize**(**fileStream**: Stream): void

**Parameters**

- **fileStream** (Stream)  


---

#### IsDBNull

**IsDBNull**(**i**: int): bool

**Parameters**

- **i** (int)  

**Returns** bool


---

#### NextResult

**NextResult**(): bool

**Returns** bool


---

#### Read

**Read**(): bool

**Returns** bool


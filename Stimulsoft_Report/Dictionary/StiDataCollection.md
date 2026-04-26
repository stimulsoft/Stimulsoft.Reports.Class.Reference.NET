---
title: "StiDataCollection Class"
---

## StiDataCollection Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Inherits from: CollectionBase  
Implements: ICloneable  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **AddRange** | void |  |
| **ClearReportDatabase** | void |  |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Contains** *(+1 overloads)* | bool |  |
| **FindByName** | [StiData](StiData.md) |  |
| **GetData** | [StiDataCollection](StiDataCollection.md) |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **RegData** *(+18 overloads)* | void |  |
| **Remove** | void |  |
| **ToList** | List<[StiData](StiData.md)> |  |

---

### Method Details

#### Add

**Add**(**data**: [StiData](StiData.md)): void

**Parameters**

- **data** ([StiData](StiData.md))  


---

#### AddRange

**AddRange**(****: StiDatadata): void

**Parameters**

- **** (StiDatadata)  


---

#### ClearReportDatabase

**ClearReportDatabase**(): void


---

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Contains

**Contains**(**data**: [StiData](StiData.md)): bool

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** bool

---

**Contains**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### FindByName

**FindByName**(**dataName**: string): [StiData](StiData.md)

**Parameters**

- **dataName** (string)  

**Returns** [StiData](StiData.md)


---

#### GetData

**GetData**(**typeData**: Type): [StiDataCollection](StiDataCollection.md)

**Parameters**

- **typeData** (Type)  

**Returns** [StiDataCollection](StiDataCollection.md)


---

#### IndexOf

**IndexOf**(**data**: [StiData](StiData.md)): int

**Parameters**

- **data** ([StiData](StiData.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **data**: [StiData](StiData.md)): void

**Parameters**

- **index** (int)  
- **data** ([StiData](StiData.md))  


---

#### RegData

**RegData**(**name**: string, **data**: object): void

**Parameters**

- **name** (string)  
- **data** (object)  

---

**RegData**(**name**: string, **dataTable**: DataTable): void

**Parameters**

- **name** (string)  
- **dataTable** (DataTable)  

---

**RegData**(**name**: string, **dataSet**: DataSet): void

**Parameters**

- **name** (string)  
- **dataSet** (DataSet)  

---

**RegData**(**name**: string, **dataView**: DataView): void

**Parameters**

- **name** (string)  
- **dataView** (DataView)  

---

**RegData**(**name**: string, **connection**: SqlConnection): void

**Parameters**

- **name** (string)  
- **connection** (SqlConnection)  

---

**RegData**(**name**: string, **connection**: OleDbConnection): void

**Parameters**

- **name** (string)  
- **connection** (OleDbConnection)  

---

**RegData**(**name**: string, **connection**: OdbcConnection): void

**Parameters**

- **name** (string)  
- **connection** (OdbcConnection)  

---

**RegData**(**name**: string, **alias**: string, **data**: object): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **data** (object)  

---

**RegData**(**data**: object): void

**Parameters**

- **data** (object)  

---

**RegData**(**name**: string, **alias**: string, **dataTable**: DataTable): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **dataTable** (DataTable)  

---

**RegData**(**name**: string, **alias**: string, **dataSet**: DataSet): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **dataSet** (DataSet)  

---

**RegData**(**name**: string, **alias**: string, **dataView**: DataView): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **dataView** (DataView)  

---

**RegData**(**name**: string, **alias**: string, **connection**: SqlConnection): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connection** (SqlConnection)  

---

**RegData**(**name**: string, **alias**: string, **connection**: OleDbConnection): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connection** (OleDbConnection)  

---

**RegData**(**name**: string, **alias**: string, **connection**: OdbcConnection): void

**Parameters**

- **name** (string)  
- **alias** (string)  
- **connection** (OdbcConnection)  

---

**RegData**(**dataTable**: DataTable): void

**Parameters**

- **dataTable** (DataTable)  

---

**RegData**(**dataSet**: DataSet): void

**Parameters**

- **dataSet** (DataSet)  

---

**RegData**(**dataView**: DataView): void

**Parameters**

- **dataView** (DataView)  

---

**RegData**(**datas**: [StiDataCollection](StiDataCollection.md)): void

**Parameters**

- **datas** ([StiDataCollection](StiDataCollection.md))  


---

#### Remove

**Remove**(**data**: [StiData](StiData.md)): void

**Parameters**

- **data** ([StiData](StiData.md))  


---

#### ToList

**ToList**(): List<[StiData](StiData.md)>

**Returns** List<[StiData](StiData.md)>


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Items** | [StiData](StiData.md)[] |  |

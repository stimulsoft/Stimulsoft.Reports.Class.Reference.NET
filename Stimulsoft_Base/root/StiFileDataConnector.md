---
title: "StiFileDataConnector Class"
---

## StiFileDataConnector Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FileType** | [StiFileType](StiFileType.md) | A type of the file which can be processed with this connection helper. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiFileDataConnector](StiFileDataConnector.md) |  |
| **GetDataSet** | DataSet | Returns DataSet based on specified options. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |

---

### Method Details

#### Get `static`

**Get**(**ident**: [StiConnectionIdent](StiConnectionIdent.md)): [StiFileDataConnector](StiFileDataConnector.md)

**Parameters**

- **ident** ([StiConnectionIdent](StiConnectionIdent.md))  

**Returns** [StiFileDataConnector](StiFileDataConnector.md)


---

#### GetDataSet

**GetDataSet**(**options**: [StiFileDataOptions](StiFileDataOptions.md)): DataSet

Returns DataSet based on specified options.

**Parameters**

- **options** ([StiFileDataOptions](StiFileDataOptions.md))  

**Returns** DataSet


---

#### RetrieveSchema

**RetrieveSchema**(**options**: [StiFileDataOptions](StiFileDataOptions.md)): [StiDataSchema](StiDataSchema.md)

Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable).

**Parameters**

- **options** ([StiFileDataOptions](StiFileDataOptions.md))  

**Returns** [StiDataSchema](StiDataSchema.md)


---

#### TestConnection

**TestConnection**(**options**: [StiFileDataOptions](StiFileDataOptions.md)): [StiTestConnectionResult](StiTestConnectionResult.md)

Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct.

**Parameters**

- **options** ([StiFileDataOptions](StiFileDataOptions.md))  

**Returns** [StiTestConnectionResult](StiTestConnectionResult.md) — The result of testing the connection string.


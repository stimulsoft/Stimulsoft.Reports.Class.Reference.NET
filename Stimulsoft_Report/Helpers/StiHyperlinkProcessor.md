---
title: "StiHyperlinkProcessor Class"
---

## StiHyperlinkProcessor Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateDataColumnName** `static` | string |  |
| **CreateFileName** `static` | string |  |
| **CreateResourceName** `static` | string |  |
| **CreateVariableName** `static` | string |  |
| **GetBytes** `static` | byte[] |  |
| **GetCloudNameFromHyperlink** `static` | string |  |
| **GetDataColumnNameFromHyperlink** `static` | string |  |
| **GetFileNameFromHyperlink** `static` | string |  |
| **GetImage** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetRealDataColumnFromHyperlink** `static` | string | Returns real-existing column name from hyperlink. Otherwise its returns null. |
| **GetResourceNameFromHyperlink** `static` | string |  |
| **GetServerNameFromHyperlink** `static` | string |  |
| **GetString** `static` | string |  |
| **GetVariableNameFromHyperlink** `static` | string |  |
| **HyperlinkToString** `static` | string |  |
| **IsCloudHyperlink** `static` | bool |  |
| **IsDataColumnHyperlink** `static` | bool |  |
| **IsFileHyperlink** `static` | bool |  |
| **IsFilePath** `static` | bool |  |
| **IsHttpOrHttpsHyperlink** `static` | bool |  |
| **IsResourceHyperlink** `static` | bool |  |
| **IsServerHyperlink** `static` | bool |  |
| **IsVariableHyperlink** `static` | bool |  |
| **TryGetBytes** `static` | byte[] |  |

---

### Method Details

#### CreateDataColumnName `static`

**CreateDataColumnName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### CreateFileName `static`

**CreateFileName**(**path**: string): string

**Parameters**

- **path** (string)  

**Returns** string


---

#### CreateResourceName `static`

**CreateResourceName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### CreateVariableName `static`

**CreateVariableName**(**name**: string): string

**Parameters**

- **name** (string)  

**Returns** string


---

#### GetBytes `static`

**GetBytes**(**report**: [StiReport](../root/StiReport.md), **hyperlink**: string, **firstPositionInDataSource**: bool, **allowDataLoading**: bool): byte[]

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **hyperlink** (string)  
- **firstPositionInDataSource** (bool)  
- **allowDataLoading** (bool)  

**Returns** byte[]


---

#### GetCloudNameFromHyperlink `static`

**GetCloudNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### GetDataColumnNameFromHyperlink `static`

**GetDataColumnNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### GetFileNameFromHyperlink `static`

**GetFileNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### GetImage `static`

**GetImage**(**report**: [StiReport](../root/StiReport.md), **hyperlink**: string, **width**: int, **height**: int): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **hyperlink** (string)  
- **width** (int)  
- **height** (int)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetRealDataColumnFromHyperlink `static`

**GetRealDataColumnFromHyperlink**(**report**: [StiReport](../root/StiReport.md), **hyperlink**: string): string

Returns real-existing column name from hyperlink. Otherwise its returns null.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **hyperlink** (string)  

**Returns** string


---

#### GetResourceNameFromHyperlink `static`

**GetResourceNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### GetServerNameFromHyperlink `static`

**GetServerNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### GetString `static`

**GetString**(**report**: [StiReport](../root/StiReport.md), **hyperlink**: string): string

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **hyperlink** (string)  

**Returns** string


---

#### GetVariableNameFromHyperlink `static`

**GetVariableNameFromHyperlink**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### HyperlinkToString `static`

**HyperlinkToString**(**hyperlink**: string): string

**Parameters**

- **hyperlink** (string)  

**Returns** string


---

#### IsCloudHyperlink `static`

**IsCloudHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsDataColumnHyperlink `static`

**IsDataColumnHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsFileHyperlink `static`

**IsFileHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsFilePath `static`

**IsFilePath**(**path**: string): bool

**Parameters**

- **path** (string)  

**Returns** bool


---

#### IsHttpOrHttpsHyperlink `static`

**IsHttpOrHttpsHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsResourceHyperlink `static`

**IsResourceHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsServerHyperlink `static`

**IsServerHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### IsVariableHyperlink `static`

**IsVariableHyperlink**(**hyperlink**: string): bool

**Parameters**

- **hyperlink** (string)  

**Returns** bool


---

#### TryGetBytes `static`

**TryGetBytes**(**report**: [StiReport](../root/StiReport.md), **hyperlink**: string, **firstPositionInDataSource**: bool, **allowDataLoading**: bool): byte[]

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **hyperlink** (string)  
- **firstPositionInDataSource** (bool)  
- **allowDataLoading** (bool)  

**Returns** byte[]


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CloudIdent** | string |  |
| **DataColumnIdent** | string |  |
| **FileIdent** | string |  |
| **HttpIdent** | string |  |
| **HttpsIdent** | string |  |
| **ResourceIdent** | string |  |
| **ServerIdent** | string |  |
| **VariableIdent** | string |  |

---
title: "StiDataParser Class"
---

## StiDataParser Class

**Namespace:** `Stimulsoft.Data.Parsers`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataParser**([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md) dictionary, DataTable table, List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)> meters) |  |

**StiDataParser**(**dictionary**: [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md), **table**: DataTable, **meters**: List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)

**Parameters**

- **dictionary** ([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md))  
- **table** (DataTable)  
- **meters** (List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Dictionary** | [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md) |  |
| **Dimensions** | [IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md)[] |  |
| **IsGrandTotal** | bool |  |
| **Meters** | IEnumerable<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)> |  |
| **Table** | DataTable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataColumnIndex** | int |  |
| **GetDimensionIndex** | int |  |
| **GetSystemVariableValue** | object |  |
| **GetVariableValue** | object |  |
| **IsSystemVariable** | bool |  |
| **IsVariable** | bool |  |
| **RunFunction** | object |  |

---

### Method Details

#### GetDataColumnIndex

**GetDataColumnIndex**(**columnName**: string): int

**Parameters**

- **columnName** (string)  

**Returns** int


---

#### GetDimensionIndex

**GetDimensionIndex**(**dimension**: [IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md)): int

**Parameters**

- **dimension** ([IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md))  

**Returns** int


---

#### GetSystemVariableValue

**GetSystemVariableValue**(**name**: string): object

**Parameters**

- **name** (string)  

**Returns** object


---

#### GetVariableValue

**GetVariableValue**(**name**: string): object

**Parameters**

- **name** (string)  

**Returns** object


---

#### IsSystemVariable

**IsSystemVariable**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### IsVariable

**IsVariable**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### RunFunction

**RunFunction**(**funcName**: string, **args**: [FunctionArgs](../Expressions/NCalc/FunctionArgs.md)): object

**Parameters**

- **funcName** (string)  
- **args** ([FunctionArgs](../Expressions/NCalc/FunctionArgs.md))  

**Returns** object


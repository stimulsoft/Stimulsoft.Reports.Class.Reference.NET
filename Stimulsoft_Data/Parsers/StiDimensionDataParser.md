---
title: "StiDimensionDataParser Class"
---

## StiDimensionDataParser Class

**Namespace:** `Stimulsoft.Data.Parsers`

### Inheritance

Inherits from: [StiDataParser](StiDataParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDimensionDataParser**([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md) dictionary, [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md) meter) |  |
| **StiDimensionDataParser**([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md) dictionary, DataTable table, List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)> meters) |  |

**StiDimensionDataParser**(**dictionary**: [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md), **meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))

**Parameters**

- **dictionary** ([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md))  
- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  

---

**StiDimensionDataParser**(**dictionary**: [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md), **table**: DataTable, **meters**: List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)

**Parameters**

- **dictionary** ([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md))  
- **table** (DataTable)  
- **meters** (List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Calculate** | object[] |  |
| **CalculateDimensionExpression** *(+1 overloads)* | object |  |

---

### Method Details

#### Calculate

**Calculate**(****: objectrow, **meters**: List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>): object[]

**Parameters**

- **** (objectrow)  
- **meters** (List<[IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md)>)  

**Returns** object[]


---

#### CalculateDimensionExpression

**CalculateDimensionExpression**(**dimension**: [IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md)): object

**Parameters**

- **dimension** ([IStiDimensionMeter](../../Stimulsoft_Base/Meters/IStiDimensionMeter.md))  

**Returns** object

---

**CalculateDimensionExpression**(**expression**: string, **throwExceptionForColumnName**: bool): object

**Parameters**

- **expression** (string)  
- **throwExceptionForColumnName** (bool)  

**Returns** object


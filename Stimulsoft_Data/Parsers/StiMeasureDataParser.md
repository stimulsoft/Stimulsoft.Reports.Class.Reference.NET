---
title: "StiMeasureDataParser Class"
---

## StiMeasureDataParser Class

**Namespace:** `Stimulsoft.Data.Parsers`

### Inheritance

Inherits from: [StiDataParser](StiDataParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMeasureDataParser**([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md) dictionary, [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md) meter) |  |

**StiMeasureDataParser**(**dictionary**: [IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md), **meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))

**Parameters**

- **dictionary** ([IStiAppDictionary](../../Stimulsoft_Base/root/IStiAppDictionary.md))  
- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Calculate** | IEnumerable<object[]> |  |
| **CalculateMeter** | object |  |

---

### Method Details

#### Calculate

**Calculate**(): IEnumerable<object[]>

**Returns** IEnumerable<object[]>


---

#### CalculateMeter

**CalculateMeter**(**meter**: [IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md), ****: objectkeys, **rows**: IEnumerable<object>): object

**Parameters**

- **meter** ([IStiMeter](../../Stimulsoft_Base/Meters/IStiMeter.md))  
- **** (objectkeys)  
- **rows** (IEnumerable<object>)  

**Returns** object


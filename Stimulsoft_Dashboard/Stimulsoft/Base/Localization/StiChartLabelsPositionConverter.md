---
title: "StiChartLabelsPositionConverter Class"
---

## StiChartLabelsPositionConverter Class

**Namespace:** `Stimulsoft.Base.Localization`

Provides a type converter to convert Enum objects to and from various other representations.

### Inheritance

Inherits from: [StiEnumConverter](../../../../Stimulsoft_Base/Localization/StiEnumConverter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiChartLabelsPositionConverter**() |  |
| **StiChartLabelsPositionConverter**(Type type) |  |

**StiChartLabelsPositionConverter**()

---

**StiChartLabelsPositionConverter**(**type**: Type)

**Parameters**

- **type** (Type)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertFrom** | object |  |
| **ConvertPositionToString** `static` | string |  |
| **ConvertStringToPosition** `static` | [StiChartLabelsPosition](../../../../Stimulsoft_Report/Dashboard/StiChartLabelsPosition.md) |  |
| **GetAcceptableValues** `static` | ArrayList |  |
| **GetStandardValues** | StandardValuesCollection |  |

---

### Method Details

#### ConvertFrom

**ConvertFrom**(**context**: ITypeDescriptorContext, **culture**: CultureInfo, **value**: object): object

**Parameters**

- **context** (ITypeDescriptorContext)  
- **culture** (CultureInfo)  
- **value** (object)  

**Returns** object


---

#### ConvertPositionToString `static`

**ConvertPositionToString**(**value**: [StiChartLabelsPosition](../../../../Stimulsoft_Report/Dashboard/StiChartLabelsPosition.md)): string

**Parameters**

- **value** ([StiChartLabelsPosition](../../../../Stimulsoft_Report/Dashboard/StiChartLabelsPosition.md))  

**Returns** string


---

#### ConvertStringToPosition `static`

**ConvertStringToPosition**(**value**: string): [StiChartLabelsPosition](../../../../Stimulsoft_Report/Dashboard/StiChartLabelsPosition.md)

**Parameters**

- **value** (string)  

**Returns** [StiChartLabelsPosition](../../../../Stimulsoft_Report/Dashboard/StiChartLabelsPosition.md)


---

#### GetAcceptableValues `static`

**GetAcceptableValues**(**context**: ITypeDescriptorContext, **withSeparators**: bool): ArrayList

**Parameters**

- **context** (ITypeDescriptorContext)  
- **withSeparators** (bool)  

**Returns** ArrayList


---

#### GetStandardValues

**GetStandardValues**(**context**: ITypeDescriptorContext): StandardValuesCollection

**Parameters**

- **context** (ITypeDescriptorContext)  

**Returns** StandardValuesCollection


---
title: "StiDialogInfo Class"
---

## StiDialogInfo Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDialogInfo**() |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, stringkeys , stringvalues ) |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, string keysColumn, string valuesColumn) |  |
| **StiDialogInfo**([StiDateTimeType](StiDateTimeType.md) type, string mask, bool allowUserValues, stringkeys , stringvalues , boolcheckedStates ) |  |

**StiDialogInfo**()

---

**StiDialogInfo**(**type**: [StiDateTimeType](StiDateTimeType.md), **mask**: string, **allowUserValues**: bool, ****: stringkeys, ****: stringvalues)

**Parameters**

- **type** ([StiDateTimeType](StiDateTimeType.md))  
- **mask** (string)  
- **allowUserValues** (bool)  
- **** (stringkeys)  
- **** (stringvalues)  

---

**StiDialogInfo**(**type**: [StiDateTimeType](StiDateTimeType.md), **mask**: string, **allowUserValues**: bool, **keysColumn**: string, **valuesColumn**: string)

**Parameters**

- **type** ([StiDateTimeType](StiDateTimeType.md))  
- **mask** (string)  
- **allowUserValues** (bool)  
- **keysColumn** (string)  
- **valuesColumn** (string)  

---

**StiDialogInfo**(**type**: [StiDateTimeType](StiDateTimeType.md), **mask**: string, **allowUserValues**: bool, ****: stringkeys, ****: stringvalues, ****: boolcheckedStates)

**Parameters**

- **type** ([StiDateTimeType](StiDateTimeType.md))  
- **mask** (string)  
- **allowUserValues** (bool)  
- **** (stringkeys)  
- **** (stringvalues)  
- **** (boolcheckedStates)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowUserValues** | bool |  |
| **BindingValue** | bool |  |
| **BindingValuesColumn** | string |  |
| **BindingVariable** | StiVariable |  |
| **CheckedColumn** | string |  |
| **CheckedStates** | bool[] |  |
| **DateTimeType** | [StiDateTimeType](StiDateTimeType.md) |  |
| **FilterExpression** | string |  |
| **ItemsInitializationType** | [StiItemsInitializationType](StiItemsInitializationType.md) |  |
| **Keys** | string[] |  |
| **KeysColumn** | string |  |
| **Mask** | string |  |
| **RememberSelection** | bool |  |
| **SortDirection** | [StiVariableSortDirection](StiVariableSortDirection.md) |  |
| **SortField** | [StiVariableSortField](StiVariableSortField.md) |  |
| **Validation** | string |  |
| **Values** | string[] |  |
| **ValuesBindingList** | List<object>[] |  |
| **ValuesColumn** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Convert** `static` | string |  |
| **GetAndParseDialogInfoItems** | List<StiDialogInfoItem> |  |
| **GetDialogInfoItems** | List<StiDialogInfoItem> |  |
| **LoadFromJsonObject** | void |  |
| **OrderBy** | List<StiDialogInfoItem> |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
| **SetDialogInfoItems** | void |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### Convert `static`

**Convert**(**value**: object): string

**Parameters**

- **value** (object)  

**Returns** string


---

#### GetAndParseDialogInfoItems

**GetAndParseDialogInfoItems**(**type**: Type, **culture**: CultureInfo, ****: stringkeys, **report**: [StiReport](../root/StiReport.md)): List<StiDialogInfoItem>

**Parameters**

- **type** (Type)  
- **culture** (CultureInfo)  
- **** (stringkeys)  
- **report** ([StiReport](../root/StiReport.md))  

**Returns** List<StiDialogInfoItem>


---

#### GetDialogInfoItems

**GetDialogInfoItems**(**type**: Type, **culture**: CultureInfo, ****: stringkeys): List<StiDialogInfoItem>

**Parameters**

- **type** (Type)  
- **culture** (CultureInfo)  
- **** (stringkeys)  

**Returns** List<StiDialogInfoItem>


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md), **report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  
- **report** ([StiReport](../root/StiReport.md))  


---

#### OrderBy

**OrderBy**(**items**: List<StiDialogInfoItem>): List<StiDialogInfoItem>

**Parameters**

- **items** (List<StiDialogInfoItem>)  

**Returns** List<StiDialogInfoItem>


---

#### SaveToJsonObject

**SaveToJsonObject**(): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


---

#### SetDialogInfoItems

**SetDialogInfoItems**(**items**: List<StiDialogInfoItem>, **type**: Type): void

**Parameters**

- **items** (List<StiDialogInfoItem>)  
- **type** (Type)  


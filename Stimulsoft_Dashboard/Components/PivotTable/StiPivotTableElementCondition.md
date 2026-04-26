---
title: "StiPivotTableElementCondition Class"
---

## StiPivotTableElementCondition Class

**Namespace:** `Stimulsoft.Dashboard.Components.PivotTable`

### Inheritance

Implements: [IStiPivotTableElementCondition](../../../Stimulsoft_Report/Dashboard/IStiPivotTableElementCondition.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPivotTableElementCondition**() |  |

**StiPivotTableElementCondition**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BackColor** | Color |  |
| **Condition** | Report.Components.StiFilterCondition |  |
| **ConditionType** | [StiPivotTableConditionType](../../../Stimulsoft_Report/Dashboard/StiPivotTableConditionType.md) |  |
| **DataType** | Report.Components.StiFilterDataType |  |
| **Font** | [Font](../../../Stimulsoft_Drawing/root/Font.md) |  |
| **Icon** | [StiFontIcons](../../../Stimulsoft_Base/Stimulsoft/Report/Helpers/StiFontIcons.md) |  |
| **IconAlignment** | [StiIconAlignment](../../../Stimulsoft_Report/Dashboard/StiIconAlignment.md) |  |
| **IconColor** | Color |  |
| **KeyValueMeter** | string |  |
| **MeasureField** | string |  |
| **Permissions** | [StiConditionPermissions](../../../Stimulsoft_Report/Components/StiConditionPermissions.md) |  |
| **TextColor** | Color |  |
| **TopNConditionCell** | bool |  |
| **TopNConditionHeader** | bool |  |
| **TopNConditionTotal** | bool |  |
| **TopNCount** | int |  |
| **TopNMode** | [StiDataTopNMode](../../../Stimulsoft_Data/Engine/StiDataTopNMode.md) |  |
| **Value** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetIcon** | byte[] |  |
| **GetUniqueCode** | int |  |
| **LoadFromJson** `static` | [StiPivotTableElementCondition](StiPivotTableElementCondition.md) |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### GetIcon

**GetIcon**(**isExporting**: bool): byte[]

**Parameters**

- **isExporting** (bool)  

**Returns** byte[]


---

#### GetUniqueCode

**GetUniqueCode**(): int

**Returns** int


---

#### LoadFromJson `static`

**LoadFromJson**(**json**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): [StiPivotTableElementCondition](StiPivotTableElementCondition.md)

**Parameters**

- **json** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  

**Returns** [StiPivotTableElementCondition](StiPivotTableElementCondition.md)


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)


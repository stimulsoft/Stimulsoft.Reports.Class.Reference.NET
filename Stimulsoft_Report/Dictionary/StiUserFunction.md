---
title: "StiUserFunction Class"
---

## StiUserFunction Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiUserFunction**() | Creates an object of the type StiUserFunction. |
| **StiUserFunction**(string name) | Creates an object of the type StiUserFunction. |
| **StiUserFunction**(string name, [StiFunctionCategory](StiFunctionCategory.md) category) | Creates an object of the type StiUserFunction. |
| **StiUserFunction**(string name, [StiFunctionCategory](StiFunctionCategory.md) category, [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md) returnType) | Creates an object of the type StiUserFunction. |

**StiUserFunction**()

Creates an object of the type StiUserFunction.

---

**StiUserFunction**(**name**: string)

Creates an object of the type StiUserFunction.

**Parameters**

- **name** (string)  

---

**StiUserFunction**(**name**: string, **category**: [StiFunctionCategory](StiFunctionCategory.md))

Creates an object of the type StiUserFunction.

**Parameters**

- **name** (string)  
- **category** ([StiFunctionCategory](StiFunctionCategory.md))  

---

**StiUserFunction**(**name**: string, **category**: [StiFunctionCategory](StiFunctionCategory.md), **returnType**: [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md))

Creates an object of the type StiUserFunction.

**Parameters**

- **name** (string)  
- **category** ([StiFunctionCategory](StiFunctionCategory.md))  
- **returnType** ([StiUserFunctionArgumentType](StiUserFunctionArgumentType.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Arguments** | StiUserFunctionArgumentsCollection |  |
| **Category** | [StiFunctionCategory](StiFunctionCategory.md) |  |
| **CustomCategory** | string |  |
| **Description** | string |  |
| **Name** | string |  |
| **ReturnType** | [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md) |  |
| **ScriptBlockly** | string |  |
| **ScriptCSharp** | string |  |
| **ScriptJS** | string |  |
| **ScriptMode** | [StiFunctionScriptMode](StiFunctionScriptMode.md) |  |
| **ScriptVB** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **GetFullScript** | string |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

#### GetFullScript

**GetFullScript**(**language**: [StiReportLanguageType](../root/StiReportLanguageType.md)): string

**Parameters**

- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  

**Returns** string


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


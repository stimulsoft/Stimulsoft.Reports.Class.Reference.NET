---
title: "StiUserFunctionHelper Class"
---

## StiUserFunctionHelper Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertArgumentTypeToString** `static` | string |  |
| **GenerateArguments** `static` | string |  |
| **GenerateFirstLineScript** `static` | string |  |
| **GenerateFunctionNameForDictionary** `static` | string |  |
| **GetArgumentType** `static` | Type |  |
| **GetCategoryName** `static` | string |  |
| **GetReturnTypeScript** `static` | string |  |
| **InvokeFunction** `static` | object |  |
| **IsNameCorrectly** `static` | bool |  |
| **IsNumericReturnType** `static` | bool |  |

---

### Method Details

#### ConvertArgumentTypeToString `static`

**ConvertArgumentTypeToString**(**type**: [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md), **language**: [StiReportLanguageType](../root/StiReportLanguageType.md)): string

**Parameters**

- **type** ([StiUserFunctionArgumentType](StiUserFunctionArgumentType.md))  
- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  

**Returns** string


---

#### GenerateArguments `static`

**GenerateArguments**(**language**: [StiReportLanguageType](../root/StiReportLanguageType.md), **function**: [StiUserFunction](StiUserFunction.md)): string

**Parameters**

- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  
- **function** ([StiUserFunction](StiUserFunction.md))  

**Returns** string


---

#### GenerateFirstLineScript `static`

**GenerateFirstLineScript**(**language**: [StiReportLanguageType](../root/StiReportLanguageType.md), **function**: [StiUserFunction](StiUserFunction.md), **showPublic**: bool): string

**Parameters**

- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  
- **function** ([StiUserFunction](StiUserFunction.md))  
- **showPublic** (bool)  

**Returns** string


---

#### GenerateFunctionNameForDictionary `static`

**GenerateFunctionNameForDictionary**(**function**: [StiUserFunction](StiUserFunction.md)): string

**Parameters**

- **function** ([StiUserFunction](StiUserFunction.md))  

**Returns** string


---

#### GetArgumentType `static`

**GetArgumentType**(**argumentType**: [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md)): Type

**Parameters**

- **argumentType** ([StiUserFunctionArgumentType](StiUserFunctionArgumentType.md))  

**Returns** Type


---

#### GetCategoryName `static`

**GetCategoryName**(**function**: [StiUserFunction](StiUserFunction.md)): string

**Parameters**

- **function** ([StiUserFunction](StiUserFunction.md))  

**Returns** string


---

#### GetReturnTypeScript `static`

**GetReturnTypeScript**(**language**: [StiReportLanguageType](../root/StiReportLanguageType.md), **function**: [StiUserFunction](StiUserFunction.md)): string

**Parameters**

- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  
- **function** ([StiUserFunction](StiUserFunction.md))  

**Returns** string


---

#### InvokeFunction `static`

**InvokeFunction**(**function**: [StiUserFunction](StiUserFunction.md), **report**: [StiReport](../root/StiReport.md), ****: objectarguments): object

**Parameters**

- **function** ([StiUserFunction](StiUserFunction.md))  
- **report** ([StiReport](../root/StiReport.md))  
- **** (objectarguments)  

**Returns** object


---

#### IsNameCorrectly `static`

**IsNameCorrectly**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### IsNumericReturnType `static`

**IsNumericReturnType**(**type**: [StiUserFunctionArgumentType](StiUserFunctionArgumentType.md)): bool

**Parameters**

- **type** ([StiUserFunctionArgumentType](StiUserFunctionArgumentType.md))  

**Returns** bool


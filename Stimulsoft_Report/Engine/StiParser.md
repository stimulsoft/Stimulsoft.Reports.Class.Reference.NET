---
title: "StiParser Class"
---

## StiParser Class

**Namespace:** `Stimulsoft.Report.Engine`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Length** | int |  |
| **Position** | int |  |
| **ProcessIifAsTernary** `static` | bool |  |
| **TypeCode** | Type |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ExecuteAsm** | object |  |
| **GetParserMethodInfo** | StiParserMethodInfo |  |
| **IsImplicitlyCastableTo** `static` | bool |  |
| **MakeTree** `static` | StiAsmNode |  |
| **ParseTextValue** `static` *(+8 overloads)* | string |  |
| **PrepareReportVariables** `static` | void |  |
| **PrepareVariableValue** `static` | object |  |
| **ToString** | string |  |

---

### Method Details

#### ExecuteAsm

**ExecuteAsm**(**objectAsmList**: object): object

**Parameters**

- **objectAsmList** (object)  

**Returns** object


---

#### GetParserMethodInfo

**GetParserMethodInfo**(**type**: StiFunctionType, ****: Typeargs, ****: objectargValues, **asmCommand**: StiAsmCommand): StiParserMethodInfo

**Parameters**

- **type** (StiFunctionType)  
- **** (Typeargs)  
- **** (objectargValues)  
- **asmCommand** (StiAsmCommand)  

**Returns** StiParserMethodInfo


---

#### IsImplicitlyCastableTo `static`

**IsImplicitlyCastableTo**(**from**: Type, **to**: Type, **valueFrom**: object): bool

**Parameters**

- **from** (Type)  
- **to** (Type)  
- **valueFrom** (object)  

**Returns** bool


---

#### MakeTree `static`

**MakeTree**(**asmList**: List<StiAsmCommand>): StiAsmNode

**Parameters**

- **asmList** (List<StiAsmCommand>)  

**Returns** StiAsmNode


---

#### ParseTextValue `static`

**ParseTextValue**(**report**: [StiReport](../root/StiReport.md), **expression**: string): string

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **expression** (string)  

**Returns** string

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **storeToPrint**: bool, **executeIfStoreToPrint**: bool): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **storeToPrint** (bool)  
- **executeIfStoreToPrint** (bool)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **storeToPrint**: bool, **executeIfStoreToPrint**: bool, **returnAsmList**: bool): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **storeToPrint** (bool)  
- **executeIfStoreToPrint** (bool)  
- **returnAsmList** (bool)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **sender**: object): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **sender** (object)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **sender**: object, **storeToPrint**: bool, **executeIfStoreToPrint**: bool): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **sender** (object)  
- **storeToPrint** (bool)  
- **executeIfStoreToPrint** (bool)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **sender**: object, **storeToPrint**: bool, **executeIfStoreToPrint**: bool, **returnAsmList**: bool): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **sender** (object)  
- **storeToPrint** (bool)  
- **executeIfStoreToPrint** (bool)  
- **returnAsmList** (bool)  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **parameters**: [StiParserParameters](StiParserParameters.md)): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **parameters** ([StiParserParameters](StiParserParameters.md))  

**Returns** object

---

**ParseTextValue**(**inputExpression**: string, **component**: StiComponent, **sender**: object, **parameters**: [StiParserParameters](StiParserParameters.md)): object

**Parameters**

- **inputExpression** (string)  
- **component** (StiComponent)  
- **sender** (object)  
- **parameters** ([StiParserParameters](StiParserParameters.md))  

**Returns** object


---

#### PrepareReportVariables `static`

**PrepareReportVariables**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### PrepareVariableValue `static`

**PrepareVariableValue**(**var**: StiVariable, **report**: [StiReport](../root/StiReport.md), **textBox**: StiText, **fillItems**: bool, **parameters**: [StiParserParameters](StiParserParameters.md), **processReadOnly**: bool): object

**Parameters**

- **var** (StiVariable)  
- **report** ([StiReport](../root/StiReport.md))  
- **textBox** (StiText)  
- **fillItems** (bool)  
- **parameters** ([StiParserParameters](StiParserParameters.md))  
- **processReadOnly** (bool)  

**Returns** object


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **LastArgsTypes** | Type[] |  |
| **LastOverload** | int |  |
| **Name** | string |  |
| **Objects** | List<object> |  |
| **Path** | List<string> |  |
| **Value** | object |  |

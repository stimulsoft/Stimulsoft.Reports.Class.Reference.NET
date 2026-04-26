---
title: "StiVariableHelper Class"
---

## StiVariableHelper Class

**Namespace:** `Stimulsoft.Report.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyVariableValue** `static` | bool |  |
| **ClearVariableLabels** `static` | void |  |
| **FillItemsOfVariable** `static` | bool |  |
| **FillItemsOfVariables** `static` | bool |  |
| **GetElementIndex** `static` | int |  |
| **GetRelatedVariablesList** `static` | List<string> |  |
| **GetVariableLabel** `static` | string |  |
| **IsVariableValueCalculateInReport** `static` | bool |  |
| **RefreshDialogInfo** `static` | void |  |
| **SetDefaultValueForRequestFromUserVariables** `static` | void |  |
| **SetDefaultValueForRequestFromUserVariablesIfUserItems** `static` | void |  |
| **SetVariableLabel** `static` | void |  |
| **SetVariableValue** `static` | void |  |

---

### Method Details

#### ApplyVariableValue `static`

**ApplyVariableValue**(**report**: [StiReport](../root/StiReport.md), **variable**: StiVariable, **variableValue**: object): bool

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **variable** (StiVariable)  
- **variableValue** (object)  

**Returns** bool


---

#### ClearVariableLabels `static`

**ClearVariableLabels**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### FillItemsOfVariable `static`

**FillItemsOfVariable**(**variable**: StiVariable, **compiledReport**: [StiReport](../root/StiReport.md), **modified**: bool, **modeItems**: bool?): bool

**Parameters**

- **variable** (StiVariable)  
- **compiledReport** ([StiReport](../root/StiReport.md))  
- **modified** (bool)  
- **modeItems** (bool?)  

**Returns** bool


---

#### FillItemsOfVariables `static`

**FillItemsOfVariables**(**compiledReport**: [StiReport](../root/StiReport.md), **modeItems**: bool?): bool

**Parameters**

- **compiledReport** ([StiReport](../root/StiReport.md))  
- **modeItems** (bool?)  

**Returns** bool


---

#### GetElementIndex `static`

**GetElementIndex**(**info**: [StiDialogInfo](../Dictionary/StiDialogInfo.md), **value**: object): int

**Parameters**

- **info** ([StiDialogInfo](../Dictionary/StiDialogInfo.md))  
- **value** (object)  

**Returns** int


---

#### GetRelatedVariablesList `static`

**GetRelatedVariablesList**(**report**: [StiReport](../root/StiReport.md), **var**: StiVariable): List<string>

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **var** (StiVariable)  

**Returns** List<string>


---

#### GetVariableLabel `static`

**GetVariableLabel**(**report**: [StiReport](../root/StiReport.md), **variableName**: string): string

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **variableName** (string)  

**Returns** string


---

#### IsVariableValueCalculateInReport `static`

**IsVariableValueCalculateInReport**(**report**: [StiReport](../root/StiReport.md), **variableName**: string): bool

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **variableName** (string)  

**Returns** bool


---

#### RefreshDialogInfo `static`

**RefreshDialogInfo**(**report**: [StiReport](../root/StiReport.md), **var**: StiVariable): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **var** (StiVariable)  


---

#### SetDefaultValueForRequestFromUserVariables `static`

**SetDefaultValueForRequestFromUserVariables**(**report**: [StiReport](../root/StiReport.md), **haveVars**: bool, **allowParseQuery**: bool, **isConnectToDataV2**: bool): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **haveVars** (bool)  
- **allowParseQuery** (bool)  
- **isConnectToDataV2** (bool)  


---

#### SetDefaultValueForRequestFromUserVariablesIfUserItems `static`

**SetDefaultValueForRequestFromUserVariablesIfUserItems**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### SetVariableLabel `static`

**SetVariableLabel**(**report**: [StiReport](../root/StiReport.md), **variable**: StiVariable, **label**: string): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **variable** (StiVariable)  
- **label** (string)  


---

#### SetVariableValue `static`

**SetVariableValue**(**report**: [StiReport](../root/StiReport.md), **variable**: StiVariable, **variableValue**: object): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **variable** (StiVariable)  
- **variableValue** (object)  


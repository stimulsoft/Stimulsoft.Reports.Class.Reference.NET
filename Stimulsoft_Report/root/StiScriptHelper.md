---
title: "StiScriptHelper Class"
---

## StiScriptHelper Class

**Namespace:** `Stimulsoft.Report`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCaching** `static` | bool |  |
| **TokenPositions** | List<StiCSharpScriptParser.TokenPosition> |  |
| **Tokens** | List<[StiToken](../../Stimulsoft_Base/root/StiToken.md)> |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ClearCache** `static` | void |  |
| **ClearTokensCache** `static` | void |  |
| **ClearTypesCache** `static` | void |  |
| **ContainsFunction** | bool |  |
| **ContainsNestedObject** | bool |  |
| **ContainsObject** | bool |  |
| **GetNestedObject** | bool |  |
| **GetObject** | object |  |
| **InvokeEventScript** `static` | object |  |
| **InvokeFunction** | object |  |
| **InvokeTextExpression** `static` | string | Parses a mixed expression containing plain text and C# code blocks in curly braces. Each block in { } is executed as C# code, the rest is treated as plain text. Example: "Text {return 1+1;} more text {return DateTime.Now.Year;}" |
| **IsAllowScriptsToRun** `static` | bool |  |
| **IsEventScript** `static` | bool |  |
| **IsObjectSupportsNesting** | bool |  |
| **IsReadOnlyObject** | bool |  |
| **IsScriptInExpression** `static` *(+1 overloads)* | bool |  |
| **ParseTextValue** `static` *(+3 overloads)* | object |  |
| **SetObject** | void |  |

---

### Method Details

#### ClearCache `static`

**ClearCache**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### ClearTokensCache `static`

**ClearTokensCache**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### ClearTypesCache `static`

**ClearTypesCache**(**report**: [StiReport](StiReport.md)): void

**Parameters**

- **report** ([StiReport](StiReport.md))  


---

#### ContainsFunction

**ContainsFunction**(**name**: string, ****: TypeargumentTypes): bool

**Parameters**

- **name** (string)  
- **** (TypeargumentTypes)  

**Returns** bool


---

#### ContainsNestedObject

**ContainsNestedObject**(**value**: object, **path**: string): bool

**Parameters**

- **value** (object)  
- **path** (string)  

**Returns** bool


---

#### ContainsObject

**ContainsObject**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### GetNestedObject

**GetNestedObject**(**value**: object, **path**: string, **result**: object): bool

**Parameters**

- **value** (object)  
- **path** (string)  
- **result** (object)  

**Returns** bool


---

#### GetObject

**GetObject**(**name**: string): object

**Parameters**

- **name** (string)  

**Returns** object


---

#### InvokeEventScript `static`

**InvokeEventScript**(**report**: [StiReport](StiReport.md), **sender**: object, **ev**: StiEvent, **args**: EventArgs): object

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **sender** (object)  
- **ev** (StiEvent)  
- **args** (EventArgs)  

**Returns** object


---

#### InvokeFunction

**InvokeFunction**(**name**: string, ****: objectarguments, ****: TypeargumentTypes): object

**Parameters**

- **name** (string)  
- **** (objectarguments)  
- **** (TypeargumentTypes)  

**Returns** object


---

#### InvokeTextExpression `static`

**InvokeTextExpression**(**report**: [StiReport](StiReport.md), **expression**: string, **arguments**: Dictionary<string, object>): string

Parses a mixed expression containing plain text and C# code blocks in curly braces. Each block in { } is executed as C# code, the rest is treated as plain text. Example: "Text {return 1+1;} more text {return DateTime.Now.Year;}"

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **expression** (string)  
- **arguments** (Dictionary<string, object>)  

**Returns** string


---

#### IsAllowScriptsToRun `static`

**IsAllowScriptsToRun**(**report**: [StiReport](StiReport.md)): bool

**Parameters**

- **report** ([StiReport](StiReport.md))  

**Returns** bool


---

#### IsEventScript `static`

**IsEventScript**(**report**: [StiReport](StiReport.md), **ev**: StiEvent): bool

**Parameters**

- **report** ([StiReport](StiReport.md))  
- **ev** (StiEvent)  

**Returns** bool


---

#### IsObjectSupportsNesting

**IsObjectSupportsNesting**(**value**: object): bool

**Parameters**

- **value** (object)  

**Returns** bool


---

#### IsReadOnlyObject

**IsReadOnlyObject**(**name**: string): bool

**Parameters**

- **name** (string)  

**Returns** bool


---

#### IsScriptInExpression `static`

**IsScriptInExpression**(**expression**: string, **component**: StiComponent): bool

**Parameters**

- **expression** (string)  
- **component** (StiComponent)  

**Returns** bool

---

**IsScriptInExpression**(**expression**: string, **report**: [StiReport](StiReport.md), **checkBraces**: bool): bool

**Parameters**

- **expression** (string)  
- **report** ([StiReport](StiReport.md))  
- **checkBraces** (bool)  

**Returns** bool


---

#### ParseTextValue `static`

**ParseTextValue**(**expression**: string, **component**: StiComponent): object

**Parameters**

- **expression** (string)  
- **component** (StiComponent)  

**Returns** object

---

**ParseTextValue**(**expression**: string, **component**: StiComponent, **sender**: object): object

**Parameters**

- **expression** (string)  
- **component** (StiComponent)  
- **sender** (object)  

**Returns** object

---

**ParseTextValue**(**expression**: string, **component**: StiComponent, **parameters**: [StiParserParameters](../Engine/StiParserParameters.md)): object

**Parameters**

- **expression** (string)  
- **component** (StiComponent)  
- **parameters** ([StiParserParameters](../Engine/StiParserParameters.md))  

**Returns** object

---

**ParseTextValue**(**expression**: string, **component**: StiComponent, **storeToPrint**: bool, **executeIfStoreToPrint**: bool, **returnAsmList**: bool): object

**Parameters**

- **expression** (string)  
- **component** (StiComponent)  
- **storeToPrint** (bool)  
- **executeIfStoreToPrint** (bool)  
- **returnAsmList** (bool)  

**Returns** object


---

#### SetObject

**SetObject**(**name**: string, **value**: object): void

**Parameters**

- **name** (string)  
- **value** (object)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **VariableChanged** | StiVariableChangedEventHandler |  |

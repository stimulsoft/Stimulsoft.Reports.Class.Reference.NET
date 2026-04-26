---
title: "Parser Class"
---

## Parser Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`

### Inheritance

Inherits from: [BaseRecognizer](BaseRecognizer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **Parser**([ITokenStream](ITokenStream.md) input) |  |
| **Parser**([ITokenStream](ITokenStream.md) input, [RecognizerSharedState](RecognizerSharedState.md) state) |  |

**Parser**(**input**: [ITokenStream](ITokenStream.md))

**Parameters**

- **input** ([ITokenStream](ITokenStream.md))  

---

**Parser**(**input**: [ITokenStream](ITokenStream.md), **state**: [RecognizerSharedState](RecognizerSharedState.md))

**Parameters**

- **input** ([ITokenStream](ITokenStream.md))  
- **state** ([RecognizerSharedState](RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCurrentInputSymbol** | object |  |
| **Reset** | void |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |

---

### Method Details

#### GetCurrentInputSymbol

**GetCurrentInputSymbol**(**input**: [IIntStream](IIntStream.md)): object

**Parameters**

- **input** ([IIntStream](IIntStream.md))  

**Returns** object


---

#### Reset

**Reset**(): void


---

#### TraceIn

**TraceIn**(**ruleName**: string, **ruleIndex**: int): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  


---

#### TraceOut

**TraceOut**(**ruleName**: string, **ruleIndex**: int): void

**Parameters**

- **ruleName** (string)  
- **ruleIndex** (int)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **input** | [ITokenStream](ITokenStream.md) |  |

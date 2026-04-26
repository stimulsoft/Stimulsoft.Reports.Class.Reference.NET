---
title: "TreeParser Class"
---

## TreeParser Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [BaseRecognizer](../BaseRecognizer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeParser**([ITreeNodeStream](ITreeNodeStream.md) input) |  |
| **TreeParser**([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state) |  |

**TreeParser**(**input**: [ITreeNodeStream](ITreeNodeStream.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  

---

**TreeParser**(**input**: [ITreeNodeStream](ITreeNodeStream.md), **state**: [RecognizerSharedState](../RecognizerSharedState.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  
- **state** ([RecognizerSharedState](../RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCurrentInputSymbol** | object |  |
| **GetErrorHeader** | string |  |
| **GetErrorMessage** | string |  |
| **GetTreeNodeStream** | [ITreeNodeStream](ITreeNodeStream.md) |  |
| **MatchAny** | void |  |
| **RecoverFromMismatchedToken** | object |  |
| **Reset** | void |  |
| **SetTreeNodeStream** | void |  |
| **TraceIn** | void |  |
| **TraceOut** | void |  |

---

### Method Details

#### GetCurrentInputSymbol

**GetCurrentInputSymbol**(**input**: [IIntStream](../IIntStream.md)): object

**Parameters**

- **input** ([IIntStream](../IIntStream.md))  

**Returns** object


---

#### GetErrorHeader

**GetErrorHeader**(**e**: [RecognitionException](../RecognitionException.md)): string

**Parameters**

- **e** ([RecognitionException](../RecognitionException.md))  

**Returns** string


---

#### GetErrorMessage

**GetErrorMessage**(**e**: [RecognitionException](../RecognitionException.md), ****: stringtokenNames): string

**Parameters**

- **e** ([RecognitionException](../RecognitionException.md))  
- **** (stringtokenNames)  

**Returns** string


---

#### GetTreeNodeStream

**GetTreeNodeStream**(): [ITreeNodeStream](ITreeNodeStream.md)

**Returns** [ITreeNodeStream](ITreeNodeStream.md)


---

#### MatchAny

**MatchAny**(**ignore**: [IIntStream](../IIntStream.md)): void

**Parameters**

- **ignore** ([IIntStream](../IIntStream.md))  


---

#### RecoverFromMismatchedToken

**RecoverFromMismatchedToken**(**input**: [IIntStream](../IIntStream.md), **ttype**: int, **follow**: [BitSet](../BitSet.md)): object

**Parameters**

- **input** ([IIntStream](../IIntStream.md))  
- **ttype** (int)  
- **follow** ([BitSet](../BitSet.md))  

**Returns** object


---

#### Reset

**Reset**(): void


---

#### SetTreeNodeStream

**SetTreeNodeStream**(**input**: [ITreeNodeStream](ITreeNodeStream.md)): void

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  


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
| **DOWN** | int |  |
| **UP** | int |  |
| **input** | [ITreeNodeStream](ITreeNodeStream.md) |  |

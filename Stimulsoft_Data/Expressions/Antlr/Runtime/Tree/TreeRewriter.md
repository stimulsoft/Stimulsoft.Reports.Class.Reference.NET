---
title: "TreeRewriter Class"
---

## TreeRewriter Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [TreeParser](TreeParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeRewriter**([ITreeNodeStream](ITreeNodeStream.md) input) |  |
| **TreeRewriter**([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state) |  |

**TreeRewriter**(**input**: [ITreeNodeStream](ITreeNodeStream.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  

---

**TreeRewriter**(**input**: [ITreeNodeStream](ITreeNodeStream.md), **state**: [RecognizerSharedState](../RecognizerSharedState.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  
- **state** ([RecognizerSharedState](../RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyOnce** | object |  |
| **ApplyRepeatedly** | object |  |
| **Bottomup** | [IAstRuleReturnScope](../IAstRuleReturnScope.md) |  |
| **Downup** *(+1 overloads)* | object |  |
| **ReportTransformation** | void |  |
| **Topdown** | [IAstRuleReturnScope](../IAstRuleReturnScope.md) |  |

---

### Method Details

#### ApplyOnce

**ApplyOnce**(**t**: object, **whichRule**: Misc.Func<[IAstRuleReturnScope](../IAstRuleReturnScope.md)>): object

**Parameters**

- **t** (object)  
- **whichRule** (Misc.Func<[IAstRuleReturnScope](../IAstRuleReturnScope.md)>)  

**Returns** object


---

#### ApplyRepeatedly

**ApplyRepeatedly**(**t**: object, **whichRule**: Misc.Func<[IAstRuleReturnScope](../IAstRuleReturnScope.md)>): object

**Parameters**

- **t** (object)  
- **whichRule** (Misc.Func<[IAstRuleReturnScope](../IAstRuleReturnScope.md)>)  

**Returns** object


---

#### Bottomup

**Bottomup**(): [IAstRuleReturnScope](../IAstRuleReturnScope.md)

**Returns** [IAstRuleReturnScope](../IAstRuleReturnScope.md)


---

#### Downup

**Downup**(**t**: object): object

**Parameters**

- **t** (object)  

**Returns** object

---

**Downup**(**t**: object, **showTransformations**: bool): object

**Parameters**

- **t** (object)  
- **showTransformations** (bool)  

**Returns** object


---

#### ReportTransformation

**ReportTransformation**(**oldTree**: object, **newTree**: object): void

**Parameters**

- **oldTree** (object)  
- **newTree** (object)  


---

#### Topdown

**Topdown**(): [IAstRuleReturnScope](../IAstRuleReturnScope.md)

**Returns** [IAstRuleReturnScope](../IAstRuleReturnScope.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **originalAdaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **originalTokenStream** | [ITokenStream](../ITokenStream.md) |  |
| **showTransformations** | bool |  |

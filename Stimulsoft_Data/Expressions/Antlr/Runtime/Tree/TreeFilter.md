---
title: "TreeFilter Class"
---

## TreeFilter Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [TreeParser](TreeParser.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeFilter**([ITreeNodeStream](ITreeNodeStream.md) input) |  |
| **TreeFilter**([ITreeNodeStream](ITreeNodeStream.md) input, [RecognizerSharedState](../RecognizerSharedState.md) state) |  |

**TreeFilter**(**input**: [ITreeNodeStream](ITreeNodeStream.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  

---

**TreeFilter**(**input**: [ITreeNodeStream](ITreeNodeStream.md), **state**: [RecognizerSharedState](../RecognizerSharedState.md))

**Parameters**

- **input** ([ITreeNodeStream](ITreeNodeStream.md))  
- **state** ([RecognizerSharedState](../RecognizerSharedState.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyOnce** | void |  |
| **Bottomup** | void |  |
| **Downup** | void |  |
| **Topdown** | void |  |

---

### Method Details

#### ApplyOnce

**ApplyOnce**(**t**: object, **whichRule**: Misc.Action): void

**Parameters**

- **t** (object)  
- **whichRule** (Misc.Action)  


---

#### Bottomup

**Bottomup**(): void


---

#### Downup

**Downup**(**t**: object): void

**Parameters**

- **t** (object)  


---

#### Topdown

**Topdown**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **originalAdaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **originalTokenStream** | [ITokenStream](../ITokenStream.md) |  |

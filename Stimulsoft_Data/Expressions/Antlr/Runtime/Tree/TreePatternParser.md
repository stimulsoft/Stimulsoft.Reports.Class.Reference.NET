---
title: "TreePatternParser Class"
---

## TreePatternParser Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Constructors

| Constructor | Description |
| --- | --- |
| **TreePatternParser**([TreePatternLexer](TreePatternLexer.md) tokenizer, [TreeWizard](TreeWizard.md) wizard, [ITreeAdaptor](ITreeAdaptor.md) adaptor) |  |

**TreePatternParser**(**tokenizer**: [TreePatternLexer](TreePatternLexer.md), **wizard**: [TreeWizard](TreeWizard.md), **adaptor**: [ITreeAdaptor](ITreeAdaptor.md))

**Parameters**

- **tokenizer** ([TreePatternLexer](TreePatternLexer.md))  
- **wizard** ([TreeWizard](TreeWizard.md))  
- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ParseNode** | object |  |
| **ParseTree** | object |  |
| **Pattern** | object |  |

---

### Method Details

#### ParseNode

**ParseNode**(): object

**Returns** object


---

#### ParseTree

**ParseTree**(): object

**Returns** object


---

#### Pattern

**Pattern**(): object

**Returns** object


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **tokenizer** | [TreePatternLexer](TreePatternLexer.md) |  |
| **ttype** | int |  |
| **wizard** | [TreeWizard](TreeWizard.md) |  |

---
title: "RewriteRuleTokenStream Class"
---

## RewriteRuleTokenStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [RewriteRuleElementStream](RewriteRuleElementStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **RewriteRuleTokenStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription) |  |
| **RewriteRuleTokenStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, object oneElement) |  |
| **RewriteRuleTokenStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, IList elements) |  |

**RewriteRuleTokenStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  

---

**RewriteRuleTokenStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **oneElement**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **oneElement** (object)  

---

**RewriteRuleTokenStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **elements**: IList)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **elements** (IList)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dup** | object |  |
| **NextNode** | object |  |
| **NextToken** | [IToken](../IToken.md) |  |
| **ToTree** | object |  |

---

### Method Details

#### Dup

**Dup**(**el**: object): object

**Parameters**

- **el** (object)  

**Returns** object


---

#### NextNode

**NextNode**(): object

**Returns** object


---

#### NextToken

**NextToken**(): [IToken](../IToken.md)

**Returns** [IToken](../IToken.md)


---

#### ToTree

**ToTree**(**el**: object): object

**Parameters**

- **el** (object)  

**Returns** object


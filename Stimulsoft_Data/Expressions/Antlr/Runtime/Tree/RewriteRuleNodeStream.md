---
title: "RewriteRuleNodeStream Class"
---

## RewriteRuleNodeStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Inheritance

Inherits from: [RewriteRuleElementStream](RewriteRuleElementStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **RewriteRuleNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription) |  |
| **RewriteRuleNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, object oneElement) |  |
| **RewriteRuleNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, IList elements) |  |

**RewriteRuleNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  

---

**RewriteRuleNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **oneElement**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **oneElement** (object)  

---

**RewriteRuleNodeStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **elements**: IList)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **elements** (IList)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dup** | object |  |
| **NextNode** | object |  |
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

#### ToTree

**ToTree**(**el**: object): object

**Parameters**

- **el** (object)  

**Returns** object


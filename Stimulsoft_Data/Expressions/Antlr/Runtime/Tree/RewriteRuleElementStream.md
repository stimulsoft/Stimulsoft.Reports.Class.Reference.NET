---
title: "RewriteRuleElementStream Class"
---

## RewriteRuleElementStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Constructors

| Constructor | Description |
| --- | --- |
| **RewriteRuleElementStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription) |  |
| **RewriteRuleElementStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, object oneElement) |  |
| **RewriteRuleElementStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, string elementDescription, IList elements) |  |

**RewriteRuleElementStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  

---

**RewriteRuleElementStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **oneElement**: object)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **oneElement** (object)  

---

**RewriteRuleElementStream**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md), **elementDescription**: string, **elements**: IList)

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  
- **elementDescription** (string)  
- **elements** (IList)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Dup** | object |  |
| **NextCore** | object |  |
| **NextTree** | object |  |
| **Reset** | void |  |
| **ToTree** | object |  |

---

### Method Details

#### Add

**Add**(**el**: object): void

**Parameters**

- **el** (object)  


---

#### Dup

**Dup**(**el**: object): object

**Parameters**

- **el** (object)  

**Returns** object


---

#### NextCore

**NextCore**(): object

**Returns** object


---

#### NextTree

**NextTree**(): object

**Returns** object


---

#### Reset

**Reset**(): void


---

#### ToTree

**ToTree**(**el**: object): object

**Parameters**

- **el** (object)  

**Returns** object


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **cursor** | int |  |
| **dirty** | bool |  |
| **elementDescription** | string |  |
| **elements** | IList |  |
| **singleElement** | object |  |

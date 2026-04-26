---
title: "TreeVisitor Class"
---

## TreeVisitor Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeVisitor**() |  |
| **TreeVisitor**([ITreeAdaptor](ITreeAdaptor.md) adaptor) |  |

**TreeVisitor**()

---

**TreeVisitor**(**adaptor**: [ITreeAdaptor](ITreeAdaptor.md))

**Parameters**

- **adaptor** ([ITreeAdaptor](ITreeAdaptor.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Visit** *(+1 overloads)* | object |  |

---

### Method Details

#### Visit

**Visit**(**t**: object, **action**: [ITreeVisitorAction](ITreeVisitorAction.md)): object

**Parameters**

- **t** (object)  
- **action** ([ITreeVisitorAction](ITreeVisitorAction.md))  

**Returns** object

---

**Visit**(**t**: object, **preAction**: Misc.Func<object, object>, **postAction**: Misc.Func<object, object>): object

**Parameters**

- **t** (object)  
- **preAction** (Misc.Func<object, object>)  
- **postAction** (Misc.Func<object, object>)  

**Returns** object


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |

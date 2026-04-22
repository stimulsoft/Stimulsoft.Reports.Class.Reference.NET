---
title: "TreeIterator Class"
---

## TreeIterator Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TreeIterator
```

### Inheritance

Implements: IEnumerator<object>  

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeIterator**([CommonTree](CommonTree.md) tree) |  |
| **TreeIterator**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **MoveNext** | bool |  |
| **Reset** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **down** | object |  |
| **eof** | object |  |
| **firstTime** | bool |  |
| **nodes** | Queue<object> |  |
| **root** | object |  |
| **tree** | object |  |
| **up** | object |  |

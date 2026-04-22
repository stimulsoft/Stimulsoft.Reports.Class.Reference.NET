---
title: "BufferedTreeNodeStream Class"
---

## BufferedTreeNodeStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class BufferedTreeNodeStream
```

### Inheritance

Implements: [ITreeNodeStream](ITreeNodeStream.md), [ITokenStreamInformation](../ITokenStreamInformation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BufferedTreeNodeStream**(object tree) |  |
| **BufferedTreeNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree) |  |
| **BufferedTreeNodeStream**([ITreeAdaptor](ITreeAdaptor.md) adaptor, object tree, int initialBufferSize) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddNavigationNode** | void |  |
| **Consume** | void |  |
| **Dispose** | void |  |
| **FillBuffer** *(+1 overloads)* | void |  |
| **GetCurrentSymbol** | object |  |
| **GetNodeIndex** | int |  |
| **Iterator** | IEnumerator<object> |  |
| **LA** | int |  |
| **LB** | object |  |
| **LT** | object |  |
| **Mark** | int |  |
| **MoveNext** | bool |  |
| **Pop** | int |  |
| **Push** | void |  |
| **Release** | void |  |
| **ReplaceChildren** | void |  |
| **Reset** *(+1 overloads)* | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **ToString** | string |  |
| **ToTokenString** | string |  |
| **ToTokenTypeString** | string |  |
| **getLastTreeNode** | object |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DEFAULT_INITIAL_BUFFER_SIZE** | int |  |
| **INITIAL_CALL_STACK_SIZE** | int |  |
| **calls** | Stack<int> |  |
| **down** | object |  |
| **eof** | object |  |
| **lastMarker** | int |  |
| **nodes** | IList |  |
| **p** | int |  |
| **root** | object |  |
| **tokens** | [ITokenStream](../ITokenStream.md) |  |
| **up** | object |  |

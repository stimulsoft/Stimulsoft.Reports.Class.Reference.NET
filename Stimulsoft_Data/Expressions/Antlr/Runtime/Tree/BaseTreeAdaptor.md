---
title: "BaseTreeAdaptor Class"
---

## BaseTreeAdaptor Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class BaseTreeAdaptor
```

### Inheritance

Implements: [ITreeAdaptor](ITreeAdaptor.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddChild** | void |  |
| **BecomeRoot** *(+1 overloads)* | object |  |
| **Create** *(+4 overloads)* | object |  |
| **CreateToken** *(+1 overloads)* | [IToken](../IToken.md) |  |
| **DeleteChild** | object |  |
| **DupNode** *(+3 overloads)* | object |  |
| **DupTree** *(+1 overloads)* | object |  |
| **GetChild** | object |  |
| **GetChildCount** | int |  |
| **GetChildIndex** | int |  |
| **GetParent** | object |  |
| **GetText** | string |  |
| **GetToken** | [IToken](../IToken.md) |  |
| **GetTokenStartIndex** | int |  |
| **GetTokenStopIndex** | int |  |
| **GetTree** | [ITree](ITree.md) |  |
| **GetType** | int |  |
| **GetUniqueID** | int |  |
| **IsNil** | bool |  |
| **Nil** | object |  |
| **ReplaceChildren** | void |  |
| **RulePostProcessing** | object |  |
| **SetChild** | void |  |
| **SetChildIndex** | void |  |
| **SetParent** | void |  |
| **SetText** | void |  |
| **SetTokenBoundaries** | void |  |
| **SetType** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **uniqueNodeID** | int |  |

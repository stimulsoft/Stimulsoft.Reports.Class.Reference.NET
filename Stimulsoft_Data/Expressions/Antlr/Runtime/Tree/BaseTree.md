---
title: "BaseTree Class"
---

## BaseTree Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public abstract class BaseTree
```

### Inheritance

Implements: [ITree](ITree.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **BaseTree**() |  |
| **BaseTree**([ITree](ITree.md) node) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddChild** | void |  |
| **AddChildren** | void |  |
| **CreateChildrenList** | IList<[ITree](ITree.md)> |  |
| **DeleteChild** | object |  |
| **DupNode** | [ITree](ITree.md) |  |
| **FreshenParentAndChildIndexes** *(+1 overloads)* | void |  |
| **FreshenParentAndChildIndexesDeeply** *(+1 overloads)* | void |  |
| **GetAncestor** | [ITree](ITree.md) |  |
| **GetAncestors** | IList<[ITree](ITree.md)> |  |
| **GetChild** | [ITree](ITree.md) |  |
| **GetFirstChildWithType** | [ITree](ITree.md) |  |
| **HasAncestor** | bool |  |
| **InsertChild** | void |  |
| **ReplaceChildren** | void |  |
| **SanityCheckParentAndChildIndexes** *(+1 overloads)* | void |  |
| **SetChild** | void |  |
| **ToString** | string |  |
| **ToStringTree** | string |  |

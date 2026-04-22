---
title: "ParseTree Class"
---

## ParseTree Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class ParseTree
```

### Inheritance

Inherits from: [BaseTree](BaseTree.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ParseTree**(object label) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DupNode** | [ITree](ITree.md) |  |
| **ToInputString** | string |  |
| **ToString** | string |  |
| **ToStringLeaves** | void |  |
| **ToStringWithHiddenTokens** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **hiddenTokens** | List<[IToken](../IToken.md)> |  |
| **payload** | object |  |

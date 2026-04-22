---
title: "TreeWizard Class"
---

## TreeWizard Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Tree`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class TreeWizard
```

### Constructors

| Constructor | Description |
| --- | --- |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor) |  |
| **TreeWizard**(stringtokenNames ) |  |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor, IDictionary<string, int> tokenNameToTypeMap) |  |
| **TreeWizard**([ITreeAdaptor](ITreeAdaptor.md) adaptor, stringtokenNames ) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** | object |  |
| **Equals** `static` *(+1 overloads)* | bool |  |
| **EqualsCore** `static` | bool |  |
| **Find** *(+1 overloads)* | IList |  |
| **FindFirst** *(+1 overloads)* | object |  |
| **GetTokenType** | int |  |
| **IndexCore** | void |  |
| **Parse** *(+1 overloads)* | bool |  |
| **ParseCore** | bool |  |
| **Visit** *(+6 overloads)* | void |  |
| **VisitCore** | void |  |
| **fillReverseIndex** | void |  |
| **getNodeIndex** | int |  |
| **reverseIndex** *(+1 overloads)* | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **INDEX_ALL** | HashSet<int> |  |
| **adaptor** | [ITreeAdaptor](ITreeAdaptor.md) |  |
| **tokenTypesToReverseIndex** | HashSet<int> |  |

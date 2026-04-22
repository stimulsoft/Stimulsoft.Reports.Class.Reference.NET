---
title: "StiLanguage Class"
---

## StiLanguage Class

**Namespace:** `Stimulsoft.Report.CodeDom`  
**Assembly:** `Stimulsoft.Report`

Base class for script languages description.

```csharp
public abstract class StiLanguage
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetGeneratedCode** `static` | string | Returns the automatically generated script from the text. |
| **GetGeneratedCodePos** `static` | void | Returns a position of the automatically generated script. |
| **GetProvider** | [StiCodeDomProvider](StiCodeDomProvider.md) | Returns a provider for this language. |
| **InsertGeneratedCode** `static` | string | Inserts the automatically generated script from the text. |
| **RemoveGeneratedCode** `static` | string | Removes the automatically generated script from the text. |
| **ReplaceGeneratedCode** `static` | string | Replace the automatically generated script for a new one. |

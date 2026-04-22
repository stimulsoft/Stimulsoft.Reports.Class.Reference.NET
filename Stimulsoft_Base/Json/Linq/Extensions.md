---
title: "Extensions Class"
---

## Extensions Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Contains the LINQ to JSON extension methods.

```csharp
public static class Extensions
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Ancestors** `static` | IJEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contains the ancestors of every token in the source collection. |
| **AncestorsAndSelf** `static` | IJEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contains every token in the source collection, and the ancestors of every token in the source collection. |
| **AsJEnumerable** `static` *(+1 overloads)* | IJEnumerable<[JToken](JToken.md)> | Returns the input typed as IJEnumerable{T}. |
| **Children** `static` *(+1 overloads)* | IJEnumerable<[JToken](JToken.md)> | Returns a collection of child tokens of every array in the source collection. |
| **Descendants** `static` | IJEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contains the descendants of every token in the source collection. |
| **DescendantsAndSelf** `static` | IJEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contains every token in the source collection, and the descendants of every token in the source collection. |
| **Properties** `static` | IJEnumerable<[JProperty](JProperty.md)> | Returns a collection of child properties of every object in the source collection. |
| **Value** `static` *(+1 overloads)* | U | Converts the value. |
| **Values** `static` *(+3 overloads)* | IJEnumerable<[JToken](JToken.md)> | Returns a collection of child values of every object in the source collection with the given key. |

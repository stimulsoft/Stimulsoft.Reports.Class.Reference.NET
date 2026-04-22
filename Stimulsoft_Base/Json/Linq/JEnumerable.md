---
title: "JEnumerable<T> Struct"
---

## JEnumerable<T> Struct

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a collection of JToken objects.

```csharp
public struct JEnumerable<T>
```

### Inheritance

Implements: IJEnumerable<T>, IEquatable<[JEnumerable](JEnumerable.md)<T>>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JEnumerable**(IEnumerable<T> enumerable) | Initializes a new instance of the JEnumerable{T} struct. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** *(+1 overloads)* | bool | Determines whether the specified JEnumerable{T} is equal to this instance. |
| **GetEnumerator** | IEnumerator<T> | Returns an enumerator that iterates through the collection. |
| **GetHashCode** | int | Returns a hash code for this instance. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [JEnumerable](JEnumerable.md)<T> | An empty collection of JToken objects. |

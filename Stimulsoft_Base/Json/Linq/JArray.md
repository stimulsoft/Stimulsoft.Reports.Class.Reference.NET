---
title: "JArray Class"
---

## JArray Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a JSON array.

```csharp
public class JArray
```

### Inheritance

Inherits from: [JContainer](JContainer.md)  
Implements: IList<[JToken](JToken.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JArray**() | Initializes a new instance of the JArray class. |
| **JArray**([JArray](JArray.md) other) | Initializes a new instance of the JArray class from another JArray object. |
| **JArray**(objectcontent ) | Initializes a new instance of the JArray class with the specified content. |
| **JArray**(object content) | Initializes a new instance of the JArray class with the specified content. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void | Adds an item to the ICollection`1. |
| **Clear** | void | Removes all items from the ICollection`1. |
| **Contains** | bool | Determines whether the ICollection`1 contains a specific value. |
| **CopyTo** | void | Copies to. |
| **FromObject** `static` *(+1 overloads)* | [JArray](JArray.md) | Creates a JArray from an object. |
| **GetEnumerator** | IEnumerator<[JToken](JToken.md)> | Returns an enumerator that iterates through the collection. |
| **IndexOf** | int | Determines the index of a specific item in the IList`1. |
| **Insert** | void | Inserts an item to the IList`1 at the specified index. |
| **Load** `static` | [JArray](JArray.md) | Loads an JArray from a JsonReader. |
| **Parse** `static` | [JArray](JArray.md) | Load a JArray from a string that contains JSON. |
| **Remove** | bool | Removes the first occurrence of a specific object from the ICollection`1. |
| **RemoveAt** | void | Removes the IList`1 item at the specified index. |
| **WriteTo** | void | Writes this token to a JsonWriter. |

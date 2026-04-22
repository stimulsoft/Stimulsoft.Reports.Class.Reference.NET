---
title: "JContainer Class"
---

## JContainer Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a token that can contain other tokens.

```csharp
public abstract class JContainer
```

### Inheritance

Inherits from: [JToken](JToken.md)  
Implements: IList<[JToken](JToken.md)>  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ChildrenTokens** | IList<[JToken](JToken.md)> | Gets the container's children tokens. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void | Adds the specified content as children of this JToken. |
| **AddFirst** | void | Adds the specified content as the first children of this JToken. |
| **Children** | [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> | Returns a collection of the child tokens of this token, in document order. |
| **CreateWriter** | [JsonWriter](../JsonWriter.md) | Creates an JsonWriter that can be used to add tokens to the JToken. |
| **Descendants** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the descendant tokens for this token in document order. |
| **DescendantsAndSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the tokens that contain this token, and all descendant tokens of this token, in document order. |
| **Equals** | bool |  |
| **GetHashCode** | int |  |
| **Merge** *(+1 overloads)* | void | Merge the specified content into this JToken. |
| **OnAddingNew** | void | Raises the AddingNew event. |
| **OnCollectionChanged** | void | Raises the CollectionChanged event. |
| **OnListChanged** | void | Raises the ListChanged event. |
| **RemoveAll** | void | Removes the child nodes from this token. |
| **ReplaceAll** | void | Replaces the children nodes of this token with the specified content. |
| **Values** | IEnumerable<T> | Returns a collection of the child values of this token, in document order. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Instance** | JTokenReferenceEqualityComparer |  |

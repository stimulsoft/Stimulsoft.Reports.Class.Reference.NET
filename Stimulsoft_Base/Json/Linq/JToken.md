---
title: "JToken Class"
---

## JToken Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents an abstract JSON token.

```csharp
public abstract class JToken
```

### Inheritance

Implements: IJEnumerable<[JToken](JToken.md)>, [IJsonLineInfo](../IJsonLineInfo.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HasValues** | bool | Gets a value indicating whether this token has child tokens. |
| **Type** | [JTokenType](JTokenType.md) | Gets the node type for this JToken. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddAfterSelf** | void | Adds the specified content immediately after this token. |
| **AddAnnotation** | void | Adds an object to the annotation list of this JToken. |
| **AddBeforeSelf** | void | Adds the specified content immediately before this token. |
| **AfterSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the sibling tokens after this token, in document order. |
| **Ancestors** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the ancestor tokens of this token. |
| **AncestorsAndSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of tokens that contain this token, and the ancestors of this token. |
| **Annotation** | object | Gets the first annotation object of the specified type from this JToken. |
| **Annotations** | IEnumerable<object> | Gets a collection of annotations of the specified type for this JToken. |
| **BeforeSelf** | IEnumerable<[JToken](JToken.md)> | Returns a collection of the sibling tokens before this token, in document order. |
| **Children** *(+1 overloads)* | [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> | Returns a collection of the child tokens of this token, in document order. |
| **CreateReader** | [JsonReader](../JsonReader.md) | Creates an JsonReader for this token. |
| **DeepClone** | [JToken](JToken.md) | Creates a new instance of the JToken. All child tokens are recursively cloned. |
| **DeepEquals** `static` | bool | Compares the values of two tokens, including the values of all descendant tokens. |
| **FromObject** `static` *(+1 overloads)* | [JToken](JToken.md) | Creates a JToken from an object. |
| **GetMetaObject** | DynamicMetaObject | Returns the DynamicMetaObject responsible for binding operations performed on this object. |
| **Load** `static` | [JToken](JToken.md) | Creates a JToken from a JsonReader. |
| **Parse** `static` | [JToken](JToken.md) | Load a JToken from a string that contains JSON. |
| **ReadFrom** `static` | [JToken](JToken.md) | Creates a JToken from a JsonReader. |
| **Remove** | void | Removes this token from its parent. |
| **RemoveAnnotations** | void | Removes the annotations of the specified type from this JToken. |
| **Replace** | void | Replaces this token with the specified token. |
| **SelectToken** *(+1 overloads)* | [JToken](JToken.md) | Selects a JToken using a JPath expression. Selects the token that matches the object path. |
| **SelectTokens** *(+1 overloads)* | IEnumerable<[JToken](JToken.md)> | Selects a collection of elements using a JPath expression. |
| **ToObject** *(+3 overloads)* | T | Creates the specified .NET type from the JToken. |
| **ToString** *(+2 overloads)* | string | Returns the indented JSON for this token. |
| **Value** | T | Gets the JToken with the specified key converted to the specified type. |
| **Values** | IEnumerable<T> | Returns a collection of the child values of this token, in document order. |
| **WriteTo** | void | Writes this token to a JsonWriter. |

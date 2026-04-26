---
title: "JContainer Class"
---

## JContainer Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a token that can contain other tokens.

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

---

### Method Details

#### Add

**Add**(**content**: object): void

Adds the specified content as children of this JToken.

**Parameters**

- **content** (object) — The content to be added.  


---

#### AddFirst

**AddFirst**(**content**: object): void

Adds the specified content as the first children of this JToken.

**Parameters**

- **content** (object) — The content to be added.  


---

#### Children

**Children**(): [JEnumerable](JEnumerable.md)<[JToken](JToken.md)>

Returns a collection of the child tokens of this token, in document order.

**Returns** [JEnumerable](JEnumerable.md)<[JToken](JToken.md)> — An IEnumerable{T} of JToken containing the child tokens of this JToken, in document order.


---

#### CreateWriter

**CreateWriter**(): [JsonWriter](../JsonWriter.md)

Creates an JsonWriter that can be used to add tokens to the JToken.

**Returns** [JsonWriter](../JsonWriter.md) — An JsonWriter that is ready to have content written to it.


---

#### Descendants

**Descendants**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of the descendant tokens for this token in document order.

**Returns** IEnumerable<[JToken](JToken.md)> — An IEnumerable{JToken} containing the descendant tokens of the JToken.


---

#### DescendantsAndSelf

**DescendantsAndSelf**(): IEnumerable<[JToken](JToken.md)>

Returns a collection of the tokens that contain this token, and all descendant tokens of this token, in document order.

**Returns** IEnumerable<[JToken](JToken.md)> — An IEnumerable{JToken} containing this token, and all the descendant tokens of the JToken.


---

#### Equals

**Equals**(**x**: [JToken](JToken.md), **y**: [JToken](JToken.md)): bool

**Parameters**

- **x** ([JToken](JToken.md))  
- **y** ([JToken](JToken.md))  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(**obj**: [JToken](JToken.md)): int

**Parameters**

- **obj** ([JToken](JToken.md))  

**Returns** int


---

#### Merge

**Merge**(**content**: object): void

Merge the specified content into this JToken.

**Parameters**

- **content** (object) — The content to be merged.  

---

**Merge**(**content**: object, **settings**: [JsonMergeSettings](JsonMergeSettings.md)): void

Merge the specified content into this JToken using JsonMergeSettings.

**Parameters**

- **content** (object) — The content to be merged.  
- **settings** ([JsonMergeSettings](JsonMergeSettings.md)) — The JsonMergeSettings used to merge the content.  


---

#### OnAddingNew

**OnAddingNew**(**e**: AddingNewEventArgs): void

Raises the AddingNew event.

**Parameters**

- **e** (AddingNewEventArgs) — The AddingNewEventArgs instance containing the event data.  


---

#### OnCollectionChanged

**OnCollectionChanged**(**e**: NotifyCollectionChangedEventArgs): void

Raises the CollectionChanged event.

**Parameters**

- **e** (NotifyCollectionChangedEventArgs) — The NotifyCollectionChangedEventArgs instance containing the event data.  


---

#### OnListChanged

**OnListChanged**(**e**: ListChangedEventArgs): void

Raises the ListChanged event.

**Parameters**

- **e** (ListChangedEventArgs) — The ListChangedEventArgs instance containing the event data.  


---

#### RemoveAll

**RemoveAll**(): void

Removes the child nodes from this token.


---

#### ReplaceAll

**ReplaceAll**(**content**: object): void

Replaces the children nodes of this token with the specified content.

**Parameters**

- **content** (object) — The content.  


---

#### Values

**Values**(): IEnumerable<T>

Returns a collection of the child values of this token, in document order.

**Returns** IEnumerable<T> — A IEnumerable{T} containing the child values of this JToken, in document order.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Instance** | JTokenReferenceEqualityComparer |  |

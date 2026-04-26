---
title: "Extensions Class"
---

## Extensions Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Contains the LINQ to JSON extension methods.

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

---

### Method Details

#### Ancestors `static`

**Ancestors**(**source**: IEnumerable<T>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of tokens that contains the ancestors of every token in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains the ancestors of every token in the source collection.


---

#### AncestorsAndSelf `static`

**AncestorsAndSelf**(**source**: IEnumerable<T>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of tokens that contains every token in the source collection, and the ancestors of every token in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains every token in the source collection, the ancestors of every token in the source collection.


---

#### AsJEnumerable `static`

**AsJEnumerable**(**source**: IEnumerable<[JToken](JToken.md)>): IJEnumerable<[JToken](JToken.md)>

Returns the input typed as IJEnumerable{T}.

**Parameters**

- **source** (IEnumerable<[JToken](JToken.md)>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — The input typed as IJEnumerable{T}.

---

**AsJEnumerable**(**source**: IEnumerable<T>): IJEnumerable<T>

Returns the input typed as IJEnumerable{T}.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<T> — The input typed as IJEnumerable{T}.


---

#### Children `static`

**Children**(**source**: IEnumerable<T>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of child tokens of every array in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains the values of every token in the source collection.

---

**Children**(**source**: IEnumerable<T>): IEnumerable<U>

Returns a collection of converted child tokens of every array in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IEnumerable<U> — An IEnumerable{T} that contains the converted values of every token in the source collection.


---

#### Descendants `static`

**Descendants**(**source**: IEnumerable<T>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of tokens that contains the descendants of every token in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains the descendants of every token in the source collection.


---

#### DescendantsAndSelf `static`

**DescendantsAndSelf**(**source**: IEnumerable<T>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of tokens that contains every token in the source collection, and the descendants of every token in the source collection.

**Parameters**

- **source** (IEnumerable<T>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains every token in the source collection, and the descendants of every token in the source collection.


---

#### Properties `static`

**Properties**(**source**: IEnumerable<[JObject](JObject.md)>): IJEnumerable<[JProperty](JProperty.md)>

Returns a collection of child properties of every object in the source collection.

**Parameters**

- **source** (IEnumerable<[JObject](JObject.md)>) — An IEnumerable{T} of JObject that contains the source collection.  

**Returns** IJEnumerable<[JProperty](JProperty.md)> — An IEnumerable{T} of JProperty that contains the properties of every object in the source collection.


---

#### Value `static`

**Value**(**value**: IEnumerable<[JToken](JToken.md)>): U

Converts the value.

**Parameters**

- **value** (IEnumerable<[JToken](JToken.md)>) — A JToken cast as a IEnumerable{T} of JToken.  

**Returns** U — A converted value.

---

**Value**(**value**: IEnumerable<T>): U

Converts the value.

**Parameters**

- **value** (IEnumerable<T>) — A JToken cast as a IEnumerable{T} of JToken.  

**Returns** U — A converted value.


---

#### Values `static`

**Values**(**source**: IEnumerable<[JToken](JToken.md)>, **key**: object): IJEnumerable<[JToken](JToken.md)>

Returns a collection of child values of every object in the source collection with the given key.

**Parameters**

- **source** (IEnumerable<[JToken](JToken.md)>) — An IEnumerable{T} of JToken that contains the source collection.  
- **key** (object) — The token key.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains the values of every token in the source collection with the given key.

---

**Values**(**source**: IEnumerable<[JToken](JToken.md)>): IJEnumerable<[JToken](JToken.md)>

Returns a collection of child values of every object in the source collection.

**Parameters**

- **source** (IEnumerable<[JToken](JToken.md)>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IJEnumerable<[JToken](JToken.md)> — An IEnumerable{T} of JToken that contains the values of every token in the source collection.

---

**Values**(**source**: IEnumerable<[JToken](JToken.md)>, **key**: object): IEnumerable<U>

Returns a collection of converted child values of every object in the source collection with the given key.

**Parameters**

- **source** (IEnumerable<[JToken](JToken.md)>) — An IEnumerable{T} of JToken that contains the source collection.  
- **key** (object) — The token key.  

**Returns** IEnumerable<U> — An IEnumerable{T} that contains the converted values of every token in the source collection with the given key.

---

**Values**(**source**: IEnumerable<[JToken](JToken.md)>): IEnumerable<U>

Returns a collection of converted child values of every object in the source collection.

**Parameters**

- **source** (IEnumerable<[JToken](JToken.md)>) — An IEnumerable{T} of JToken that contains the source collection.  

**Returns** IEnumerable<U> — An IEnumerable{T} that contains the converted values of every token in the source collection.


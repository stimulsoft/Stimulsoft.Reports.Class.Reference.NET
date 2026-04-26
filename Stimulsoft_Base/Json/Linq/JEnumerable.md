---
title: "JEnumerable<T> Struct"
---

## JEnumerable<T> Struct

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a collection of JToken objects.

### Inheritance

Implements: IJEnumerable<T>, IEquatable<[JEnumerable](JEnumerable.md)<T>>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JEnumerable**(IEnumerable<T> enumerable) | Initializes a new instance of the JEnumerable{T} struct. |

**JEnumerable**(**enumerable**: IEnumerable<T>)

Initializes a new instance of the JEnumerable{T} struct.

**Parameters**

- **enumerable** (IEnumerable<T>) — The enumerable.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** *(+1 overloads)* | bool | Determines whether the specified JEnumerable{T} is equal to this instance. |
| **GetEnumerator** | IEnumerator<T> | Returns an enumerator that iterates through the collection. |
| **GetHashCode** | int | Returns a hash code for this instance. |

---

### Method Details

#### Equals

**Equals**(**other**: [JEnumerable](JEnumerable.md)<T>): bool

Determines whether the specified JEnumerable{T} is equal to this instance.

**Parameters**

- **other** ([JEnumerable](JEnumerable.md)<T>) — The JEnumerable{T} to compare with this instance.  

**Returns** bool — `true` if the specified JEnumerable{T} is equal to this instance; otherwise, `false`.

---

**Equals**(**obj**: object): bool

Determines whether the specified Object is equal to this instance.

**Parameters**

- **obj** (object) — The Object to compare with this instance.  

**Returns** bool — `true` if the specified Object is equal to this instance; otherwise, `false`.


---

#### GetEnumerator

**GetEnumerator**(): IEnumerator<T>

Returns an enumerator that iterates through the collection.

**Returns** IEnumerator<T> — A IEnumerator`1 that can be used to iterate through the collection.


---

#### GetHashCode

**GetHashCode**(): int

Returns a hash code for this instance.

**Returns** int — A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [JEnumerable](JEnumerable.md)<T> | An empty collection of JToken objects. |

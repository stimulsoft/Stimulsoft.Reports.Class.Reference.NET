---
title: "JTokenEqualityComparer Class"
---

## JTokenEqualityComparer Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Compares tokens to determine whether they are equal.

### Inheritance

Implements: IEqualityComparer<[JToken](JToken.md)>  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool | Determines whether the specified objects are equal. |
| **GetHashCode** | int | Returns a hash code for the specified object. |

---

### Method Details

#### Equals

**Equals**(**x**: [JToken](JToken.md), **y**: [JToken](JToken.md)): bool

Determines whether the specified objects are equal.

**Parameters**

- **x** ([JToken](JToken.md)) — The first object of type JToken to compare.  
- **y** ([JToken](JToken.md)) — The second object of type JToken to compare.  

**Returns** bool — true if the specified objects are equal; otherwise, false.


---

#### GetHashCode

**GetHashCode**(**obj**: [JToken](JToken.md)): int

Returns a hash code for the specified object.

**Parameters**

- **obj** ([JToken](JToken.md)) — The Object for which a hash code is to be returned.  

**Returns** int — A hash code for the specified object.


---
title: "JsonPropertyCollection Class"
---

## JsonPropertyCollection Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

A collection of JsonProperty objects.

### Inheritance

Inherits from: KeyedCollection<string, [JsonProperty](JsonProperty.md)>  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonPropertyCollection**(Type type) | Initializes a new instance of the JsonPropertyCollection class. |

**JsonPropertyCollection**(**type**: Type)

Initializes a new instance of the JsonPropertyCollection class.

**Parameters**

- **type** (Type) — The type.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddProperty** | void | Adds a JsonProperty object. |
| **GetClosestMatchProperty** | [JsonProperty](JsonProperty.md) | Gets the closest matching JsonProperty object. First attempts to get an exact case match of propertyName and then a case insensitive match. |
| **GetKeyForItem** | string | When implemented in a derived class, extracts the key from the specified element. |
| **GetProperty** | [JsonProperty](JsonProperty.md) | Gets a property by property name. |

---

### Method Details

#### AddProperty

**AddProperty**(**property**: [JsonProperty](JsonProperty.md)): void

Adds a JsonProperty object.

**Parameters**

- **property** ([JsonProperty](JsonProperty.md)) — The property to add to the collection.  


---

#### GetClosestMatchProperty

**GetClosestMatchProperty**(**propertyName**: string): [JsonProperty](JsonProperty.md)

Gets the closest matching JsonProperty object. First attempts to get an exact case match of propertyName and then a case insensitive match.

**Parameters**

- **propertyName** (string) — Name of the property.  

**Returns** [JsonProperty](JsonProperty.md) — A matching property if found.


---

#### GetKeyForItem

**GetKeyForItem**(**item**: [JsonProperty](JsonProperty.md)): string

When implemented in a derived class, extracts the key from the specified element.

**Parameters**

- **item** ([JsonProperty](JsonProperty.md)) — The element from which to extract the key.  

**Returns** string — The key for the specified element.


---

#### GetProperty

**GetProperty**(**propertyName**: string, **comparisonType**: StringComparison): [JsonProperty](JsonProperty.md)

Gets a property by property name.

**Parameters**

- **propertyName** (string) — The name of the property to get.  
- **comparisonType** (StringComparison) — Type property name string comparison.  

**Returns** [JsonProperty](JsonProperty.md) — A matching property if found.


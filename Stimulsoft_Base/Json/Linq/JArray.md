---
title: "JArray Class"
---

## JArray Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a JSON array.

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

**JArray**()

Initializes a new instance of the JArray class.

---

**JArray**(**other**: [JArray](JArray.md))

Initializes a new instance of the JArray class from another JArray object.

**Parameters**

- **other** ([JArray](JArray.md)) — A JArray object to copy from.  

---

**JArray**(****: objectcontent)

Initializes a new instance of the JArray class with the specified content.

**Parameters**

- **** (objectcontent)  

---

**JArray**(**content**: object)

Initializes a new instance of the JArray class with the specified content.

**Parameters**

- **content** (object) — The contents of the array.  


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

---

### Method Details

#### Add

**Add**(**item**: [JToken](JToken.md)): void

Adds an item to the ICollection`1.

**Parameters**

- **item** ([JToken](JToken.md)) — The object to add to the ICollection`1.  


---

#### Clear

**Clear**(): void

Removes all items from the ICollection`1.


---

#### Contains

**Contains**(**item**: [JToken](JToken.md)): bool

Determines whether the ICollection`1 contains a specific value.

**Parameters**

- **item** ([JToken](JToken.md)) — The object to locate in the ICollection`1.  

**Returns** bool — true if is found in the ICollection`1; otherwise, false.


---

#### CopyTo

**CopyTo**(****: JTokenarray, **arrayIndex**: int): void

Copies to.

**Parameters**

- **** (JTokenarray)  
- **arrayIndex** (int) — Index of the array.  


---

#### FromObject `static`

**FromObject**(**o**: object): [JArray](JArray.md)

Creates a JArray from an object.

**Parameters**

- **o** (object) — The object that will be used to create JArray.  

**Returns** [JArray](JArray.md) — A JArray with the values of the specified object

---

**FromObject**(**o**: object, **jsonSerializer**: [JsonSerializer](../../Json2/JsonSerializer.md)): [JArray](JArray.md)

Creates a JArray from an object.

**Parameters**

- **o** (object) — The object that will be used to create JArray.  
- **jsonSerializer** ([JsonSerializer](../../Json2/JsonSerializer.md)) — The JsonSerializer that will be used to read the object.  

**Returns** [JArray](JArray.md) — A JArray with the values of the specified object


---

#### GetEnumerator

**GetEnumerator**(): IEnumerator<[JToken](JToken.md)>

Returns an enumerator that iterates through the collection.

**Returns** IEnumerator<[JToken](JToken.md)> — A IEnumerator`1 that can be used to iterate through the collection.


---

#### IndexOf

**IndexOf**(**item**: [JToken](JToken.md)): int

Determines the index of a specific item in the IList`1.

**Parameters**

- **item** ([JToken](JToken.md)) — The object to locate in the IList`1.  

**Returns** int — The index of if found in the list; otherwise, -1.


---

#### Insert

**Insert**(**index**: int, **item**: [JToken](JToken.md)): void

Inserts an item to the IList`1 at the specified index.

**Parameters**

- **index** (int) — The zero-based index at which should be inserted.  
- **item** ([JToken](JToken.md)) — The object to insert into the IList`1.  


---

#### Load `static`

**Load**(**reader**: [JsonReader](../JsonReader.md)): [JArray](JArray.md)

Loads an JArray from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — A JsonReader that will be read for the content of the JArray.  

**Returns** [JArray](JArray.md) — A JArray that contains the JSON that was read from the specified JsonReader.


---

#### Parse `static`

**Parse**(**json**: string): [JArray](JArray.md)

Load a JArray from a string that contains JSON.

**Parameters**

- **json** (string) — A String that contains JSON.  

**Returns** [JArray](JArray.md) — A JArray populated from the string that contains JSON.


---

#### Remove

**Remove**(**item**: [JToken](JToken.md)): bool

Removes the first occurrence of a specific object from the ICollection`1.

**Parameters**

- **item** ([JToken](JToken.md)) — The object to remove from the ICollection`1.  

**Returns** bool — true if was successfully removed from the ICollection`1; otherwise, false. This method also returns false if is not found in the original ICollection`1.


---

#### RemoveAt

**RemoveAt**(**index**: int): void

Removes the IList`1 item at the specified index.

**Parameters**

- **index** (int) — The zero-based index of the item to remove.  


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  


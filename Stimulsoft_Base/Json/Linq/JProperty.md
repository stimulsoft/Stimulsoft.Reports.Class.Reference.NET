---
title: "JProperty Class"
---

## JProperty Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a JSON property.

### Inheritance

Inherits from: [JContainer](JContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JProperty**([JProperty](JProperty.md) other) | Initializes a new instance of the JProperty class from another JProperty object. |
| **JProperty**(string name, objectcontent ) | Initializes a new instance of the JProperty class. |
| **JProperty**(string name, object content) | Initializes a new instance of the JProperty class. |

**JProperty**(**other**: [JProperty](JProperty.md))

Initializes a new instance of the JProperty class from another JProperty object.

**Parameters**

- **other** ([JProperty](JProperty.md)) — A JProperty object to copy from.  

---

**JProperty**(**name**: string, ****: objectcontent)

Initializes a new instance of the JProperty class.

**Parameters**

- **name** (string) — The property name.  
- **** (objectcontent)  

---

**JProperty**(**name**: string, **content**: object)

Initializes a new instance of the JProperty class.

**Parameters**

- **name** (string) — The property name.  
- **content** (object) — The property content.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Clear** | void |  |
| **Contains** | bool |  |
| **CopyTo** | void |  |
| **GetEnumerator** | IEnumerator<[JToken](JToken.md)> |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Load** `static` | [JProperty](JProperty.md) | Loads an JProperty from a JsonReader. |
| **Remove** | bool |  |
| **RemoveAt** | void |  |
| **WriteTo** | void | Writes this token to a JsonWriter. |

---

### Method Details

#### Add

**Add**(**item**: [JToken](JToken.md)): void

**Parameters**

- **item** ([JToken](JToken.md))  


---

#### Clear

**Clear**(): void


---

#### Contains

**Contains**(**item**: [JToken](JToken.md)): bool

**Parameters**

- **item** ([JToken](JToken.md))  

**Returns** bool


---

#### CopyTo

**CopyTo**(****: JTokenarray, **arrayIndex**: int): void

**Parameters**

- **** (JTokenarray)  
- **arrayIndex** (int)  


---

#### GetEnumerator

**GetEnumerator**(): IEnumerator<[JToken](JToken.md)>

**Returns** IEnumerator<[JToken](JToken.md)>


---

#### IndexOf

**IndexOf**(**item**: [JToken](JToken.md)): int

**Parameters**

- **item** ([JToken](JToken.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **item**: [JToken](JToken.md)): void

**Parameters**

- **index** (int)  
- **item** ([JToken](JToken.md))  


---

#### Load `static`

**Load**(**reader**: [JsonReader](../JsonReader.md)): [JProperty](JProperty.md)

Loads an JProperty from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — A JsonReader that will be read for the content of the JProperty.  

**Returns** [JProperty](JProperty.md) — A JProperty that contains the JSON that was read from the specified JsonReader.


---

#### Remove

**Remove**(**item**: [JToken](JToken.md)): bool

**Parameters**

- **item** ([JToken](JToken.md))  

**Returns** bool


---

#### RemoveAt

**RemoveAt**(**index**: int): void

**Parameters**

- **index** (int)  


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  


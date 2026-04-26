---
title: "JConstructor Class"
---

## JConstructor Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a JSON constructor.

### Inheritance

Inherits from: [JContainer](JContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JConstructor**() | Initializes a new instance of the JConstructor class. |
| **JConstructor**([JConstructor](JConstructor.md) other) | Initializes a new instance of the JConstructor class from another JConstructor object. |
| **JConstructor**(string name) | Initializes a new instance of the JConstructor class with the specified name. |
| **JConstructor**(string name, objectcontent ) | Initializes a new instance of the JConstructor class with the specified name and content. |
| **JConstructor**(string name, object content) | Initializes a new instance of the JConstructor class with the specified name and content. |

**JConstructor**()

Initializes a new instance of the JConstructor class.

---

**JConstructor**(**other**: [JConstructor](JConstructor.md))

Initializes a new instance of the JConstructor class from another JConstructor object.

**Parameters**

- **other** ([JConstructor](JConstructor.md)) — A JConstructor object to copy from.  

---

**JConstructor**(**name**: string)

Initializes a new instance of the JConstructor class with the specified name.

**Parameters**

- **name** (string) — The constructor name.  

---

**JConstructor**(**name**: string, ****: objectcontent)

Initializes a new instance of the JConstructor class with the specified name and content.

**Parameters**

- **name** (string) — The constructor name.  
- **** (objectcontent)  

---

**JConstructor**(**name**: string, **content**: object)

Initializes a new instance of the JConstructor class with the specified name and content.

**Parameters**

- **name** (string) — The constructor name.  
- **content** (object) — The contents of the constructor.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** `static` | [JConstructor](JConstructor.md) | Loads an JConstructor from a JsonReader. |
| **WriteTo** | void | Writes this token to a JsonWriter. |

---

### Method Details

#### Load `static`

**Load**(**reader**: [JsonReader](../JsonReader.md)): [JConstructor](JConstructor.md)

Loads an JConstructor from a JsonReader.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — A JsonReader that will be read for the content of the JConstructor.  

**Returns** [JConstructor](JConstructor.md) — A JConstructor that contains the JSON that was read from the specified JsonReader.


---

#### WriteTo

**WriteTo**(**writer**: [JsonWriter](../JsonWriter.md), ****: JsonConverterconverters): void

Writes this token to a JsonWriter.

**Parameters**

- **writer** ([JsonWriter](../JsonWriter.md)) — A JsonWriter into which this method will write.  
- **** (JsonConverterconverters)  


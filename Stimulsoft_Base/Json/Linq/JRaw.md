---
title: "JRaw Class"
---

## JRaw Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a raw JSON string.

### Inheritance

Inherits from: [JValue](JValue.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **JRaw**([JRaw](JRaw.md) other) | Initializes a new instance of the JRaw class from another JRaw object. |
| **JRaw**(object rawJson) | Initializes a new instance of the JRaw class. |

**JRaw**(**other**: [JRaw](JRaw.md))

Initializes a new instance of the JRaw class from another JRaw object.

**Parameters**

- **other** ([JRaw](JRaw.md)) — A JRaw object to copy from.  

---

**JRaw**(**rawJson**: object)

Initializes a new instance of the JRaw class.

**Parameters**

- **rawJson** (object) — The raw json.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Create** `static` | [JRaw](JRaw.md) | Creates an instance of JRaw with the content of the reader's current token. |

---

### Method Details

#### Create `static`

**Create**(**reader**: [JsonReader](../JsonReader.md)): [JRaw](JRaw.md)

Creates an instance of JRaw with the content of the reader's current token.

**Parameters**

- **reader** ([JsonReader](../JsonReader.md)) — The reader.  

**Returns** [JRaw](JRaw.md) — An instance of JRaw with the content of the reader's current token.


---
title: "Extensions Class"
---

## Extensions Class

**Namespace:** `Stimulsoft.Base.Json.Schema`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsValid** `static` *(+1 overloads)* | bool |  |
| **Validate** `static` *(+1 overloads)* | void |  |

---

### Method Details

#### IsValid `static`

**IsValid**(**source**: [JToken](../Linq/JToken.md), **schema**: [JsonSchema](JsonSchema.md)): bool

**Parameters**

- **source** ([JToken](../Linq/JToken.md))  
- **schema** ([JsonSchema](JsonSchema.md))  

**Returns** bool

---

**IsValid**(**source**: [JToken](../Linq/JToken.md), **schema**: [JsonSchema](JsonSchema.md), **errorMessages**: IList<string>): bool

**Parameters**

- **source** ([JToken](../Linq/JToken.md))  
- **schema** ([JsonSchema](JsonSchema.md))  
- **errorMessages** (IList<string>)  

**Returns** bool


---

#### Validate `static`

**Validate**(**source**: [JToken](../Linq/JToken.md), **schema**: [JsonSchema](JsonSchema.md)): void

**Parameters**

- **source** ([JToken](../Linq/JToken.md))  
- **schema** ([JsonSchema](JsonSchema.md))  

---

**Validate**(**source**: [JToken](../Linq/JToken.md), **schema**: [JsonSchema](JsonSchema.md), **validationEventHandler**: ValidationEventHandler): void

**Parameters**

- **source** ([JToken](../Linq/JToken.md))  
- **schema** ([JsonSchema](JsonSchema.md))  
- **validationEventHandler** (ValidationEventHandler)  


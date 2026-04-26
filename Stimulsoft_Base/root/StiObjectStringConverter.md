---
title: "StiObjectStringConverter Class"
---

## StiObjectStringConverter Class

**Namespace:** `Stimulsoft.Base`

Helps a converts object to string and a converts string to object.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ObjectToString** | string | Converts object into the string. |
| **SetProperty** | void |  |
| **StringToObject** | object | Convertes string into object. |

---

### Method Details

#### ObjectToString

**ObjectToString**(**obj**: object): string

Converts object into the string.

**Parameters**

- **obj** (object) — Object for convertation.  

**Returns** string — String that represents object.


---

#### SetProperty

**SetProperty**(**p**: PropertyInfo, **parentObject**: object, **obj**: object): void

**Parameters**

- **p** (PropertyInfo)  
- **parentObject** (object)  
- **obj** (object)  


---

#### StringToObject

**StringToObject**(**str**: string, **type**: Type): object

Convertes string into object.

**Parameters**

- **str** (string) — String that represents object.  
- **type** (Type) — Object type.  

**Returns** object — Converted object.


---
title: "StiObjectStateSaver Class"
---

## StiObjectStateSaver Class

**Namespace:** `Stimulsoft.Base`

This class helps with searialing/deserializing state of object to string.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ReadObjectStateFromString** `static` *(+1 overloads)* | void | Read object state from string. |
| **WriteObjectStateToString** `static` *(+1 overloads)* | string | Write object state to string. |

---

### Method Details

#### ReadObjectStateFromString `static`

**ReadObjectStateFromString**(**obj**: object, **str**: string): void

Read object state from string.

**Parameters**

- **obj** (object) — Object for storing state.  
- **str** (string) — String which contain state of object.  

---

**ReadObjectStateFromString**(**obj**: object, **str**: string, **converter**: [StiObjectStringConverter](StiObjectStringConverter.md)): void

Read object state from string.

**Parameters**

- **obj** (object) — Object for storing state.  
- **str** (string) — String which contain state of object.  
- **converter** ([StiObjectStringConverter](StiObjectStringConverter.md)) — Object converter which used for writing to string.  


---

#### WriteObjectStateToString `static`

**WriteObjectStateToString**(**obj**: object): string

Write object state to string.

**Parameters**

- **obj** (object) — Object which state will be save to string.  

**Returns** string — String which contains string representation of object.

---

**WriteObjectStateToString**(**obj**: object, **converter**: [StiObjectStringConverter](StiObjectStringConverter.md)): string

Object which state will be save to string.

**Parameters**

- **obj** (object) — Object which state will be save to string.  
- **converter** ([StiObjectStringConverter](StiObjectStringConverter.md)) — Object converter which used for writing to string.  

**Returns** string — String which contain string representation of object.


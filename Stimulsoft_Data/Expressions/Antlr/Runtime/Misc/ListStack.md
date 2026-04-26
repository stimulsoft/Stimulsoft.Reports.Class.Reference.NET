---
title: "ListStack<T> Class"
---

## ListStack<T> Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime.Misc`

### Inheritance

Inherits from: List<T>  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Peek** *(+1 overloads)* | T |  |
| **Pop** | T |  |
| **Push** | void |  |
| **TryPeek** *(+1 overloads)* | bool |  |
| **TryPop** | bool |  |

---

### Method Details

#### Peek

**Peek**(): T

**Returns** T

---

**Peek**(**depth**: int): T

**Parameters**

- **depth** (int)  

**Returns** T


---

#### Pop

**Pop**(): T

**Returns** T


---

#### Push

**Push**(**item**: T): void

**Parameters**

- **item** (T)  


---

#### TryPeek

**TryPeek**(**item**: T): bool

**Parameters**

- **item** (T)  

**Returns** bool

---

**TryPeek**(**depth**: int, **item**: T): bool

**Parameters**

- **depth** (int)  
- **item** (T)  

**Returns** bool


---

#### TryPop

**TryPop**(**item**: T): bool

**Parameters**

- **item** (T)  

**Returns** bool


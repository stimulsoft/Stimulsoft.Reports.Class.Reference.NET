---
title: "DefaultSerializationBinder Class"
---

## DefaultSerializationBinder Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

The default serialization binder used when resolving and loading classes from type names.

### Inheritance

Inherits from: [SerializationBinder](../SerializationBinder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BindToName** | void | When overridden in a derived class, controls the binding of a serialized object to a type. |
| **BindToType** | Type | When overridden in a derived class, controls the binding of a serialized object to a type. |
| **Equals** *(+1 overloads)* | bool |  |
| **GetHashCode** | int |  |

---

### Method Details

#### BindToName

**BindToName**(**serializedType**: Type, **assemblyName**: string, **typeName**: string): void

When overridden in a derived class, controls the binding of a serialized object to a type.

**Parameters**

- **serializedType** (Type) — The type of the object the formatter creates a new instance of.  
- **assemblyName** (string) — Specifies the Assembly name of the serialized object.  
- **typeName** (string) — Specifies the Type name of the serialized object.  


---

#### BindToType

**BindToType**(**assemblyName**: string, **typeName**: string): Type

When overridden in a derived class, controls the binding of a serialized object to a type.

**Parameters**

- **assemblyName** (string) — Specifies the Assembly name of the serialized object.  
- **typeName** (string) — Specifies the Type name of the serialized object.  

**Returns** Type — The type of the object the formatter creates a new instance of.


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool

---

**Equals**(**other**: TypeNameKey): bool

**Parameters**

- **other** (TypeNameKey)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


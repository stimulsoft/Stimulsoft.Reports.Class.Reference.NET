---
title: "SerializationBinder Class"
---

## SerializationBinder Class

**Namespace:** `Stimulsoft.Base.Json`

Allows users to control class loading and mandate what class to load.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BindToName** | void | When overridden in a derived class, controls the binding of a serialized object to a type. |
| **BindToType** | Type | When overridden in a derived class, controls the binding of a serialized object to a type. |

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
- **typeName** (string) — Specifies the Type name of the serialized object  

**Returns** Type — The type of the object the formatter creates a new instance of.


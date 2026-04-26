---
title: "ReflectionAttributeProvider Class"
---

## ReflectionAttributeProvider Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Provides methods to get attributes from a Type, MemberInfo, ParameterInfo or Assembly.

### Inheritance

Implements: [IAttributeProvider](IAttributeProvider.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ReflectionAttributeProvider**(object attributeProvider) | Initializes a new instance of the ReflectionAttributeProvider class. |

**ReflectionAttributeProvider**(**attributeProvider**: object)

Initializes a new instance of the ReflectionAttributeProvider class.

**Parameters**

- **attributeProvider** (object) — The instance to get attributes for. This parameter should be a Type, MemberInfo, ParameterInfo or Assembly.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAttributes** *(+1 overloads)* | IList<Attribute> | Returns a collection of all of the attributes, or an empty collection if there are no attributes. |

---

### Method Details

#### GetAttributes

**GetAttributes**(**inherit**: bool): IList<Attribute>

Returns a collection of all of the attributes, or an empty collection if there are no attributes.

**Parameters**

- **inherit** (bool) — When true, look up the hierarchy chain for the inherited custom attribute.  

**Returns** IList<Attribute> — A collection of Attributes, or an empty collection.

---

**GetAttributes**(**attributeType**: Type, **inherit**: bool): IList<Attribute>

Returns a collection of attributes, identified by type, or an empty collection if there are no attributes.

**Parameters**

- **attributeType** (Type) — The type of the attributes.  
- **inherit** (bool) — When true, look up the hierarchy chain for the inherited custom attribute.  

**Returns** IList<Attribute> — A collection of Attributes, or an empty collection.


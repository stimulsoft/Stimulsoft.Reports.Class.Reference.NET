---
title: "ReflectionAttributeProvider Class"
---

## ReflectionAttributeProvider Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Provides methods to get attributes from a Type, MemberInfo, ParameterInfo or Assembly.

```csharp
public class ReflectionAttributeProvider
```

### Inheritance

Implements: [IAttributeProvider](IAttributeProvider.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `ReflectionAttributeProvider(object attributeProvider)` | Initializes a new instance of the ReflectionAttributeProvider class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAttributes** *(+1 overloads)* | IList<Attribute> | Returns a collection of all of the attributes, or an empty collection if there are no attributes. |

---
title: "StiReference Class"
---

## StiReference Class

**Namespace:** `Stimulsoft.Base.Serializing`

Class for delayed processing references (references which allude to the unprocessed objects).

### Constructors

| Constructor | Description |
| --- | --- |
| **StiReference**([StiPropertyInfo](StiPropertyInfo.md) propInfo) | Creates a new instance of the StiReference class. |
| **StiReference**([StiPropertyInfo](StiPropertyInfo.md) propInfo, object obj, PropertyInfo propertyInfo) | Creates a new instance of the StiReference class. |

**StiReference**(**propInfo**: [StiPropertyInfo](StiPropertyInfo.md))

Creates a new instance of the StiReference class.

**Parameters**

- **propInfo** ([StiPropertyInfo](StiPropertyInfo.md)) — Adapted property.  

---

**StiReference**(**propInfo**: [StiPropertyInfo](StiPropertyInfo.md), **obj**: object, **propertyInfo**: PropertyInfo)

Creates a new instance of the StiReference class.

**Parameters**

- **propInfo** ([StiPropertyInfo](StiPropertyInfo.md)) — Adapted property.  
- **obj** (object) — The object where a property is located.  
- **propertyInfo** (PropertyInfo) — Standard property.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Object** | object | Gets or sets the object where a property is located. |
| **PropInfo** | [StiPropertyInfo](StiPropertyInfo.md) | Gets or sets the adapted property. |
| **PropertyInfo** | PropertyInfo | Gets or sets standard property. |

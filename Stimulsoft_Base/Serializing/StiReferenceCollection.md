---
title: "StiReferenceCollection Class"
---

## StiReferenceCollection Class

**Namespace:** `Stimulsoft.Base.Serializing`

Describes a collection of delayed references.

### Inheritance

Inherits from: CollectionBase  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** *(+2 overloads)* | void |  |
| **AddRange** *(+1 overloads)* | void |  |
| **Contains** | bool |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Remove** | void |  |

---

### Method Details

#### Add

**Add**(**propInfo**: [StiPropertyInfo](StiPropertyInfo.md)): void

**Parameters**

- **propInfo** ([StiPropertyInfo](StiPropertyInfo.md))  

---

**Add**(**propInfo**: [StiPropertyInfo](StiPropertyInfo.md), **value**: object, **propertyInfo**: PropertyInfo): void

**Parameters**

- **propInfo** ([StiPropertyInfo](StiPropertyInfo.md))  
- **value** (object)  
- **propertyInfo** (PropertyInfo)  

---

**Add**(**reference**: [StiReference](StiReference.md)): void

**Parameters**

- **reference** ([StiReference](StiReference.md))  


---

#### AddRange

**AddRange**(****: StiReferencereference): void

**Parameters**

- **** (StiReferencereference)  

---

**AddRange**(**references**: [StiReferenceCollection](StiReferenceCollection.md)): void

**Parameters**

- **references** ([StiReferenceCollection](StiReferenceCollection.md))  


---

#### Contains

**Contains**(**reference**: [StiReference](StiReference.md)): bool

**Parameters**

- **reference** ([StiReference](StiReference.md))  

**Returns** bool


---

#### IndexOf

**IndexOf**(**reference**: [StiReference](StiReference.md)): int

**Parameters**

- **reference** ([StiReference](StiReference.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **reference**: [StiReference](StiReference.md)): void

**Parameters**

- **index** (int)  
- **reference** ([StiReference](StiReference.md))  


---

#### Remove

**Remove**(**reference**: [StiReference](StiReference.md)): void

**Parameters**

- **reference** ([StiReference](StiReference.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Items** | [StiReference](StiReference.md)[] |  |

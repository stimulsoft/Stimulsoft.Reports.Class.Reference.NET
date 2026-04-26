---
title: "StiPropertyInfoCollection Class"
---

## StiPropertyInfoCollection Class

**Namespace:** `Stimulsoft.Base.Serializing`

Describes a collection of object properties.

### Inheritance

Inherits from: CollectionBase  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPropertyInfoCollection**() |  |
| **StiPropertyInfoCollection**([StiPropertyInfo](StiPropertyInfo.md) parentPropertyInfo) |  |

**StiPropertyInfoCollection**()

---

**StiPropertyInfoCollection**(**parentPropertyInfo**: [StiPropertyInfo](StiPropertyInfo.md))

**Parameters**

- **parentPropertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **AddRange** *(+1 overloads)* | void |  |
| **Contains** | bool |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Remove** | void |  |

---

### Method Details

#### Add

**Add**(**propertyInfo**: [StiPropertyInfo](StiPropertyInfo.md)): void

**Parameters**

- **propertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  


---

#### AddRange

**AddRange**(****: StiPropertyInfopropertyInfos): void

**Parameters**

- **** (StiPropertyInfopropertyInfos)  

---

**AddRange**(**propertyInfos**: [StiPropertyInfoCollection](StiPropertyInfoCollection.md)): void

**Parameters**

- **propertyInfos** ([StiPropertyInfoCollection](StiPropertyInfoCollection.md))  


---

#### Contains

**Contains**(**propertyInfo**: [StiPropertyInfo](StiPropertyInfo.md)): bool

**Parameters**

- **propertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  

**Returns** bool


---

#### IndexOf

**IndexOf**(**propertyInfo**: [StiPropertyInfo](StiPropertyInfo.md)): int

**Parameters**

- **propertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **propertyInfo**: [StiPropertyInfo](StiPropertyInfo.md)): void

**Parameters**

- **index** (int)  
- **propertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  


---

#### Remove

**Remove**(**propertyInfo**: [StiPropertyInfo](StiPropertyInfo.md)): void

**Parameters**

- **propertyInfo** ([StiPropertyInfo](StiPropertyInfo.md))  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Items** | [StiPropertyInfo](StiPropertyInfo.md)[] |  |

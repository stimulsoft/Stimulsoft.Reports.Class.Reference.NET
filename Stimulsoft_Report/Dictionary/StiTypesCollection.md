---
title: "StiTypesCollection Class"
---

## StiTypesCollection Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Collection of the registered types.

### Inheritance

Inherits from: CollectionBase  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **AddRange** *(+1 overloads)* | void |  |
| **Contains** | bool |  |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **RegType** | void | Registers type. |
| **Remove** | void |  |
| **ToList** | List<[StiType](StiType.md)> |  |

---

### Method Details

#### Add

**Add**(**type**: [StiType](StiType.md)): void

**Parameters**

- **type** ([StiType](StiType.md))  


---

#### AddRange

**AddRange**(****: StiTypetype): void

**Parameters**

- **** (StiTypetype)  

---

**AddRange**(**types**: [StiTypesCollection](StiTypesCollection.md)): void

**Parameters**

- **types** ([StiTypesCollection](StiTypesCollection.md))  


---

#### Contains

**Contains**(**type**: [StiType](StiType.md)): bool

**Parameters**

- **type** ([StiType](StiType.md))  

**Returns** bool


---

#### IndexOf

**IndexOf**(**type**: [StiType](StiType.md)): int

**Parameters**

- **type** ([StiType](StiType.md))  

**Returns** int


---

#### Insert

**Insert**(**index**: int, **type**: [StiType](StiType.md)): void

**Parameters**

- **index** (int)  
- **type** ([StiType](StiType.md))  


---

#### RegType

**RegType**(**name**: string, **type**: Type): void

Registers type.

**Parameters**

- **name** (string) — Name of type.  
- **type** (Type) — Type.  


---

#### Remove

**Remove**(**type**: [StiType](StiType.md)): void

**Parameters**

- **type** ([StiType](StiType.md))  


---

#### ToList

**ToList**(): List<[StiType](StiType.md)>

**Returns** List<[StiType](StiType.md)>


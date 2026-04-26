---
title: "StiTypeFinder Class"
---

## StiTypeFinder Class

**Namespace:** `Stimulsoft.Base`

Class contains statistic methods to find types.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FindInterface** `static` | bool | Finds in the type exType interface findType. |
| **FindType** `static` | bool | Finds in the type exType the type findType. |
| **GetType** `static` | Type | Returns the type from its string representation. |

---

### Method Details

#### FindInterface `static`

**FindInterface**(**exType**: Type, **interfaceForFinding**: Type): bool

Finds in the type exType interface findType.

**Parameters**

- **exType** (Type) — Examined type.  
- **interfaceForFinding** (Type) — Interface for finding.  

**Returns** bool — true, if interface is not found.


---

#### FindType `static`

**FindType**(**exType**: Type, **typeForFinding**: Type): bool

Finds in the type exType the type findType.

**Parameters**

- **exType** (Type) — Examined type.  
- **typeForFinding** (Type) — Type for finding.  

**Returns** bool — true, if type is not found.


---

#### GetType `static`

**GetType**(**typeName**: string, **ignoreCase**: bool): Type

Returns the type from its string representation.

**Parameters**

- **typeName** (string)  
- **ignoreCase** (bool)  

**Returns** Type


### Events

| Event | Type | Description |
| --- | --- | --- |
| **TypeNotFound** | StiTypeNotFoundEventHandler |  |
| **TypeResolve** | EventHandler<[StiTypeEventArgs](StiTypeEventArgs.md)> |  |

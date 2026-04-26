---
title: "StiService Class"
---

## StiService Class

**Namespace:** `Stimulsoft.Base.Services`

### Inheritance

Implements: ICloneable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ServiceType** | Type |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **IsPropertiesInitializedProtected** | bool | Internal use only, for LoadDocument optimization. |
| **IsPropertyPresent** | bool |  |
| **PackService** | void |  |

---

### Method Details

#### Clone

**Clone**(): object

Creates a new object that is a copy of the current instance.

**Returns** object — A new object that is a copy of this instance.


---

#### IsPropertiesInitializedProtected

**IsPropertiesInitializedProtected**(): bool

Internal use only, for LoadDocument optimization.

**Returns** bool — Returns true if Properties property is initialized.


---

#### IsPropertyPresent

**IsPropertyPresent**(**key**: object): bool

**Parameters**

- **key** (object)  

**Returns** bool


---

#### PackService

**PackService**(): void


---
title: "JPropertyDescriptor Class"
---

## JPropertyDescriptor Class

**Namespace:** `Stimulsoft.Base.Json.Linq`

Represents a view of a JProperty.

### Inheritance

Inherits from: PropertyDescriptor  

### Constructors

| Constructor | Description |
| --- | --- |
| **JPropertyDescriptor**(string name) | Initializes a new instance of the JPropertyDescriptor class. |

**JPropertyDescriptor**(**name**: string)

Initializes a new instance of the JPropertyDescriptor class.

**Parameters**

- **name** (string) — The name.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanResetValue** | bool | When overridden in a derived class, returns whether resetting an object changes its value. |
| **GetValue** | object | When overridden in a derived class, gets the current value of the property on a component. |
| **ResetValue** | void | When overridden in a derived class, resets the value for this property of the component to the default value. |
| **SetValue** | void | When overridden in a derived class, sets the value of the component to a different value. |
| **ShouldSerializeValue** | bool | When overridden in a derived class, determines a value indicating whether the value of this property needs to be persisted. |

---

### Method Details

#### CanResetValue

**CanResetValue**(**component**: object): bool

When overridden in a derived class, returns whether resetting an object changes its value.

**Parameters**

- **component** (object) — The component to test for reset capability.  

**Returns** bool — true if resetting the component changes its value; otherwise, false.


---

#### GetValue

**GetValue**(**component**: object): object

When overridden in a derived class, gets the current value of the property on a component.

**Parameters**

- **component** (object) — The component with the property for which to retrieve the value.  

**Returns** object — The value of a property for a given component.


---

#### ResetValue

**ResetValue**(**component**: object): void

When overridden in a derived class, resets the value for this property of the component to the default value.

**Parameters**

- **component** (object) — The component with the property value that is to be reset to the default value.  


---

#### SetValue

**SetValue**(**component**: object, **value**: object): void

When overridden in a derived class, sets the value of the component to a different value.

**Parameters**

- **component** (object) — The component with the property value that is to be set.  
- **value** (object) — The new value.  


---

#### ShouldSerializeValue

**ShouldSerializeValue**(**component**: object): bool

When overridden in a derived class, determines a value indicating whether the value of this property needs to be persisted.

**Parameters**

- **component** (object) — The component with the property to be examined for persistence.  

**Returns** bool — true if the property should be persisted; otherwise, false.


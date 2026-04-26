---
title: "StiPropertyDescriptor Class"
---

## StiPropertyDescriptor Class

**Namespace:** `Stimulsoft.Base.Localization`

Provides an abstraction of a property on a class.

### Inheritance

Inherits from: PropertyDescriptor  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPropertyDescriptor**(PropertyDescriptor propertyDescriptor) | Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified PropertyDescriptor. |
| **StiPropertyDescriptor**(PropertyDescriptor propertyDescriptor, bool isEventDescriptor) | Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified StiPropertyDescriptor. |

**StiPropertyDescriptor**(**propertyDescriptor**: PropertyDescriptor)

Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified PropertyDescriptor.

**Parameters**

- **propertyDescriptor** (PropertyDescriptor) — Specified PropertyDescriptor.  

---

**StiPropertyDescriptor**(**propertyDescriptor**: PropertyDescriptor, **isEventDescriptor**: bool)

Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified StiPropertyDescriptor.

**Parameters**

- **propertyDescriptor** (PropertyDescriptor) — Specified SPropertyDescriptor.  
- **isEventDescriptor** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsLocalizableProperties** | bool |  |
| **PropertyDescriptor** | PropertyDescriptor |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanResetValue** | bool | Returns whether resetting an object changes its value. |
| **GetEditor** | object |  |
| **GetValue** | object | Gets the current value of the property on a component. |
| **InvokeProcessDescription** `static` | void |  |
| **ResetValue** | void | Resets the value for this property of the component to the default value. |
| **SetValue** | void | Sets the value of the component to a different value. |
| **ShouldSerializeValue** | bool | Determines a value indicating whether the value of this property needs to be persisted. |
| **ToString** | string |  |

---

### Method Details

#### CanResetValue

**CanResetValue**(**component**: object): bool

Returns whether resetting an object changes its value.

**Parameters**

- **component** (object) — The component to test for reset capability.  

**Returns** bool — true if resetting the component changes its value; otherwise, false.


---

#### GetEditor

**GetEditor**(**editorBaseType**: Type): object

**Parameters**

- **editorBaseType** (Type)  

**Returns** object


---

#### GetValue

**GetValue**(**component**: object): object

Gets the current value of the property on a component.

**Parameters**

- **component** (object) — The component with the property for which to retrieve the value.  

**Returns** object — The value of a property for a given component.


---

#### InvokeProcessDescription `static`

**InvokeProcessDescription**(**sender**: object, **e**: [StiProcessDescriptionEventArgs](../Design/StiProcessDescriptionEventArgs.md)): void

**Parameters**

- **sender** (object)  
- **e** ([StiProcessDescriptionEventArgs](../Design/StiProcessDescriptionEventArgs.md))  


---

#### ResetValue

**ResetValue**(**component**: object): void

Resets the value for this property of the component to the default value.

**Parameters**

- **component** (object) — The component with the property value that is to be reset to the default value.  


---

#### SetValue

**SetValue**(**component**: object, **value**: object): void

Sets the value of the component to a different value.

**Parameters**

- **component** (object) — The component with the property value that is to be set.  
- **value** (object) — The new value.  


---

#### ShouldSerializeValue

**ShouldSerializeValue**(**component**: object): bool

Determines a value indicating whether the value of this property needs to be persisted.

**Parameters**

- **component** (object) — The component with the property to be examined for persistence.  

**Returns** bool — true if the property should be persisted; otherwise, false.


---

#### ToString

**ToString**(): string

**Returns** string


### Events

| Event | Type | Description |
| --- | --- | --- |
| **ProcessDescription** | StiProcessDescriptionEventHandler |  |

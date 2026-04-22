---
title: "StiPropertyDescriptor Class"
---

## StiPropertyDescriptor Class

**Namespace:** `Stimulsoft.Base.Localization`  
**Assembly:** `Stimulsoft.Base`

Provides an abstraction of a property on a class.

```csharp
public class StiPropertyDescriptor
```

### Inheritance

Inherits from: PropertyDescriptor  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPropertyDescriptor**(PropertyDescriptor propertyDescriptor) | Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified PropertyDescriptor. |
| **StiPropertyDescriptor**(PropertyDescriptor propertyDescriptor, bool isEventDescriptor) | Initializes a new instance of the StiPropertyDescriptor class with the name and attributes in the specified StiPropertyDescriptor. |

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

### Events

| Event | Type | Description |
| --- | --- | --- |
| **ProcessDescription** | StiProcessDescriptionEventHandler |  |

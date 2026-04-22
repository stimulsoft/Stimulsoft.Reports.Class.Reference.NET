---
title: "StiDataBindingPropertyDescriptor Class"
---

## StiDataBindingPropertyDescriptor Class

**Namespace:** `Stimulsoft.Base.Design`  
**Assembly:** `Stimulsoft.Report`

Provides an abstraction of a property on a class.

```csharp
public class StiDataBindingPropertyDescriptor
```

### Inheritance

Inherits from: [StiPropertyDescriptor](../../../../Stimulsoft_Base/Localization/StiPropertyDescriptor.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataBindingPropertyDescriptor**(PropertyDescriptor propertyDescriptor) | Initializes a new instance of the PropertyDescriptor class with the name and attributes in the specified PropertyDescriptor. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanResetValue** | bool | Returns whether resetting an object changes its value. |
| **GetValue** | object | Gets the current value of the property on a component. |
| **ResetValue** | void | Resets the value for this property of the component to the default value. |
| **SetValue** | void | Sets the value of the component to a different value. |
| **ShouldSerializeValue** | bool | Determines a value indicating whether the value of this property needs to be persisted. |

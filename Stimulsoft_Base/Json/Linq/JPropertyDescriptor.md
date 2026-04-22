---
title: "JPropertyDescriptor Class"
---

## JPropertyDescriptor Class

**Namespace:** `Stimulsoft.Base.Json.Linq`  
**Assembly:** `Stimulsoft.Base`

Represents a view of a JProperty.

```csharp
public class JPropertyDescriptor
```

### Inheritance

Inherits from: PropertyDescriptor  

### Constructors

| Constructor | Description |
| --- | --- |
| `JPropertyDescriptor(string name)` | Initializes a new instance of the JPropertyDescriptor class. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanResetValue** | bool | When overridden in a derived class, returns whether resetting an object changes its value. |
| **GetValue** | object | When overridden in a derived class, gets the current value of the property on a component. |
| **ResetValue** | void | When overridden in a derived class, resets the value for this property of the component to the default value. |
| **SetValue** | void | When overridden in a derived class, sets the value of the component to a different value. |
| **ShouldSerializeValue** | bool | When overridden in a derived class, determines a value indicating whether the value of this property needs to be persisted. |

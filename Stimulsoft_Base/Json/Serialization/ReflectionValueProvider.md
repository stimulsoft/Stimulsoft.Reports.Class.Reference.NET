---
title: "ReflectionValueProvider Class"
---

## ReflectionValueProvider Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Get and set values for a MemberInfo using reflection.

### Inheritance

Implements: [IValueProvider](IValueProvider.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **ReflectionValueProvider**(MemberInfo memberInfo) | Initializes a new instance of the ReflectionValueProvider class. |

**ReflectionValueProvider**(**memberInfo**: MemberInfo)

Initializes a new instance of the ReflectionValueProvider class.

**Parameters**

- **memberInfo** (MemberInfo) — The member info.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetValue** | object | Gets the value. |
| **SetValue** | void | Sets the value. |

---

### Method Details

#### GetValue

**GetValue**(**target**: object): object

Gets the value.

**Parameters**

- **target** (object) — The target to get the value from.  

**Returns** object — The value.


---

#### SetValue

**SetValue**(**target**: object, **value**: object): void

Sets the value.

**Parameters**

- **target** (object) — The target to set the value on.  
- **value** (object) — The value to set on the target.  


---
title: "StiTypeWrapper Class"
---

## StiTypeWrapper Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

Class describes a wrapper for the type.

```csharp
public class StiTypeWrapper
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTypeWrapper**(Type type) | Creates a new instance of the StiTypeWrapper class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Type** | Type | Gets or sets the Type for which is described wrapper. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBaseTypeWrappers** `static` | [StiTypeWrapper](StiTypeWrapper.md)[] | Gets the array of base simple types. |
| **GetTypeWrappers** `static` | [StiTypeWrapper](StiTypeWrapper.md)[] | Gets the array of simple types. |
| **IsAllowedType** `static` | bool | Returns true if specified type is a simple type for Stimulsoft Reports. |
| **ToString** *(+1 overloads)* | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **SimpleTypes** | List<Type> |  |

---
title: "SizeD Struct"
---

## SizeD Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct SizeD
```

### Inheritance

Implements: [IStiDefault](../Design/IStiDefault.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `SizeD(double width, double height)` | Initializes a new instance of the SizeD class from the specified dimensions. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | double |  |
| **Width** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateFromSize** `static` | [SizeD](SizeD.md) | Creates a new SizeD object based on the specified SizeF object. |
| **Equals** | bool | Tests to see whether the specified object is a SizeD with the same dimensions as this SizeD. |
| **GetHashCode** | int | Returns a hash code for this SizeD structure. |
| **Multiply** | [SizeD](SizeD.md) | Multiplies the size on number. |
| **ToSize** | Size | Converts the specified SizeD to a Size. |
| **ToSizeF** | SizeF |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [SizeD](SizeD.md) | Initializes a new instance of the SizeD class. |
| **IsDefault** | bool |  |
| **IsEmpty** | bool |  |

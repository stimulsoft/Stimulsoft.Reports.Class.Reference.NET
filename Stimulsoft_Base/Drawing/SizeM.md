---
title: "SizeM Struct"
---

## SizeM Struct

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public struct SizeM
```

### Inheritance

Implements: [IStiDefault](../Design/IStiDefault.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **SizeM**(decimal width, decimal height) | Initializes a new instance of the SizeM class from the specified dimensions. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | decimal |  |
| **Width** | decimal |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Equals** | bool | Tests to see whether the specified object is a SizeM with the same dimensions as this SizeM. |
| **GetHashCode** | int | Returns a hash code for this SizeM structure. |
| **ToSizeD** | [SizeD](SizeD.md) |  |
| **ToSizeF** | SizeF |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [SizeM](SizeM.md) | Initializes a new instance of the SizeM class. |
| **IsDefault** | bool |  |
| **IsEmpty** | bool |  |

---
title: "StiSimpleBorder Class"
---

## StiSimpleBorder Class

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiSimpleBorder
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSimpleBorder**() | Creates a new instance of the StiSimpleBorder class. |
| **StiSimpleBorder**([StiBorderSides](StiBorderSides.md) side, Color color, double size, [StiPenStyle](StiPenStyle.md) style) | Creates a new instance of the StiSimpleBorder class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Color** | Color |  |
| **Side** | [StiBorderSides](StiBorderSides.md) |  |
| **Size** | double |  |
| **Style** | [StiPenStyle](StiPenStyle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Draw** *(+4 overloads)* | void | Draws this border on the indicated Graphics. |
| **Equals** | bool | Tests to see whether the specified object is a StiSimpleBorder with the same dimensions as this StiSimpleBorder. |
| **GetBorder** | StiBorder |  |
| **GetHashCode** | int | Returns a hash code for this StiPaddings structure. |
| **GetSizeOffset** | float |  |
| **LoadFromJson** | void |  |

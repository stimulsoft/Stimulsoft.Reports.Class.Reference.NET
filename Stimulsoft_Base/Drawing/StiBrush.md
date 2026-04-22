---
title: "StiBrush Class"
---

## StiBrush Class

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class StiBrush
```

### Inheritance

Implements: ICloneable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Ident** | [StiBrushIdent](StiBrushIdent.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Dark** `static` | [StiBrush](StiBrush.md) |  |
| **Equals** | bool |  |
| **GetBrush** `static` *(+2 overloads)* | [Brush](../../Stimulsoft_Drawing/Brush.md) | Returns the gdi brush from the report brush. |
| **GetHashCode** | int |  |
| **GetImage** | [Image](../../Stimulsoft_Drawing/Image.md) |  |
| **IsEmpty** `static` | bool | Returns true if this brush is empty - brush is null or StiEmptyBrush. |
| **IsTransparent** `static` | bool | Returns true if this brush is transparent - brush is null, empty or solid and color is transparent. |
| **Light** `static` | [StiBrush](StiBrush.md) |  |
| **LoadFromJson** `static` | [StiBrush](StiBrush.md) |  |
| **ToColor** `static` | Color | Transform a brush into a color. |

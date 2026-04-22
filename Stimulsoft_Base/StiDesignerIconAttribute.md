---
title: "StiDesignerIconAttribute Class"
---

## StiDesignerIconAttribute Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiDesignerIconAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDesignerIconAttribute**(Type type, string bitmapName) | Creates a new attribute of the type StiDataAdapterIconAttribute. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BitmapName** | string | Gets or sets a path to the bitmap in resources. |
| **Type** | Type | Gets or sets service type to which a bitmap is assign to. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** `static` *(+1 overloads)* | [Bitmap](../Stimulsoft_Drawing/Bitmap.md) | Returns a service image according to its type. |
| **GetImagePath** `static` | string | Returns a path to image according to its type. |

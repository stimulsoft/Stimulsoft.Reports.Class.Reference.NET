---
title: "StiServiceCategoryBitmapAttribute Class"
---

## StiServiceCategoryBitmapAttribute Class

**Namespace:** `Stimulsoft.Base.Services`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiServiceCategoryBitmapAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServiceCategoryBitmapAttribute**(Type type, string bitmapName) | Creates a new attribute of the type StiServiceCategoryBitmapAttribute. |
| **StiServiceCategoryBitmapAttribute**(Type type, string bitmapName, string bigBitmapName) | Creates a new attribute of the type StiServiceCategoryBitmapAttribute. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BigBitmapName** | string | Gets or sets a path to the big bitmap in resources. |
| **BigBitmapNameDark** | string | Gets or sets a path to the big bitmap in resources. |
| **BitmapName** | string | Gets or sets a path to a bitmap in resources. |
| **BitmapNameDark** | string | Gets or sets a path to the bitmap in resources. |
| **Type** | Type | Gets or sets service type to which a bitmap is assign to. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBigImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/Bitmap.md) | Returns a big service image according to its type. |
| **GetImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/Bitmap.md) | Returns a bitmap of service category according to its type. |
| **GetImagePath** `static` | string | Returns a path to image according to its type. |

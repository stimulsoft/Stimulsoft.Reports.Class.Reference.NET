---
title: "StiServiceBitmapAttribute Class"
---

## StiServiceBitmapAttribute Class

**Namespace:** `Stimulsoft.Base.Services`  
**Assembly:** `Stimulsoft.Base`

```csharp
public sealed class StiServiceBitmapAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServiceBitmapAttribute**(Type type, string bitmapName) | Creates a new attribute of the type StiServiceBitmapAttribute. |
| **StiServiceBitmapAttribute**(Type type, string bitmapName, string bigBitmapName) | Creates a new attribute of the type StiServiceBitmapAttribute. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BigBitmapName** | string | Gets or sets a path to the big bitmap in resources. |
| **BigBitmapNameDark** | string | Gets or sets a path to the big bitmap in resources. |
| **BitmapName** | string | Gets or sets a path to the bitmap in resources. |
| **BitmapNameDark** | string | Gets or sets a path to the bitmap in resources. |
| **Type** | Type | Gets or sets service type to which a bitmap is assign to. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBigImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/Bitmap.md) | Returns a big service image according to its type. |
| **GetImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/Bitmap.md) | Returns a service image according to its type. |
| **GetImagePath** `static` | string | Returns a path to an image according to its type. |

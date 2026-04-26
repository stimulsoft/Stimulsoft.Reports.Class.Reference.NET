---
title: "StiServiceBitmapAttribute Class"
---

## StiServiceBitmapAttribute Class

**Namespace:** `Stimulsoft.Base.Services`

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServiceBitmapAttribute**(Type type, string bitmapName) | Creates a new attribute of the type StiServiceBitmapAttribute. |
| **StiServiceBitmapAttribute**(Type type, string bitmapName, string bigBitmapName) | Creates a new attribute of the type StiServiceBitmapAttribute. |

**StiServiceBitmapAttribute**(**type**: Type, **bitmapName**: string)

Creates a new attribute of the type StiServiceBitmapAttribute.

**Parameters**

- **type** (Type) — Service type to which a bitmap is compared to.  
- **bitmapName** (string) — A path to the bitmap in resources.  

---

**StiServiceBitmapAttribute**(**type**: Type, **bitmapName**: string, **bigBitmapName**: string)

Creates a new attribute of the type StiServiceBitmapAttribute.

**Parameters**

- **type** (Type) — Service type to which a bitmap is compared to.  
- **bitmapName** (string) — A path to the bitmap in resources.  
- **bigBitmapName** (string) — A path to the big bitmap in resources.  


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
| **GetBigImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Returns a big service image according to its type. |
| **GetImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Returns a service image according to its type. |
| **GetImagePath** `static` | string | Returns a path to an image according to its type. |

---

### Method Details

#### GetBigImage `static`

**GetBigImage**(**type**: Type, **isDark**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns a big service image according to its type.

**Parameters**

- **type** (Type) — A service type.  
- **isDark** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — A big image.

---

**GetBigImage**(**isDark**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns an big image of this type.

**Parameters**

- **isDark** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — A big image.


---

#### GetImage `static`

**GetImage**(**type**: Type, **isDark**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns a service image according to its type.

**Parameters**

- **type** (Type) — A service type.  
- **isDark** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — An image.

---

**GetImage**(**isDark**: bool): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns an image of this type.

**Parameters**

- **isDark** (bool)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — An image.


---

#### GetImagePath `static`

**GetImagePath**(**type**: Type): string

Returns a path to an image according to its type.

**Parameters**

- **type** (Type) — A service type.  

**Returns** string — A path to an image.


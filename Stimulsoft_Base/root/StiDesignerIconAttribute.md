---
title: "StiDesignerIconAttribute Class"
---

## StiDesignerIconAttribute Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDesignerIconAttribute**(Type type, string bitmapName) | Creates a new attribute of the type StiDataAdapterIconAttribute. |

**StiDesignerIconAttribute**(**type**: Type, **bitmapName**: string)

Creates a new attribute of the type StiDataAdapterIconAttribute.

**Parameters**

- **type** (Type) — Service type to which a bitmap is compared to.  
- **bitmapName** (string) — A path to the bitmap in resources.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BitmapName** | string | Gets or sets a path to the bitmap in resources. |
| **Type** | Type | Gets or sets service type to which a bitmap is assign to. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetImage** `static` *(+1 overloads)* | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) | Returns a service image according to its type. |
| **GetImagePath** `static` | string | Returns a path to image according to its type. |

---

### Method Details

#### GetImage `static`

**GetImage**(**type**: Type): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns a service image according to its type.

**Parameters**

- **type** (Type) — Service type.  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — Image.

---

**GetImage**(): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

Returns an image of this type.

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) — Image.


---

#### GetImagePath `static`

**GetImagePath**(**type**: Type): string

Returns a path to image according to its type.

**Parameters**

- **type** (Type) — Service type.  

**Returns** string — Path to Image.


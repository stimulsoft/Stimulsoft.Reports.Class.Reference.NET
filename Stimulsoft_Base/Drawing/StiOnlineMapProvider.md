---
title: "StiOnlineMapProvider Class"
---

## StiOnlineMapProvider Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawImage** `static` | void |  |
| **GetImage** `static` *(+1 overloads)* | byte[] |  |
| **GetScript** `static` | string |  |

---

### Method Details

#### DrawImage `static`

**DrawImage**(**element**: [IStiAppComponent](../root/IStiAppComponent.md), **size**: Size, **mapData**: Hashtable, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **location**: [RectangleD](RectangleD.md), **elementKey**: string, **uniqueCode**: int, **ignoreSize**: bool, **isExporting**: bool): void

**Parameters**

- **element** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **size** (Size)  
- **mapData** (Hashtable)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **location** ([RectangleD](RectangleD.md))  
- **elementKey** (string)  
- **uniqueCode** (int)  
- **ignoreSize** (bool)  
- **isExporting** (bool)  


---

#### GetImage `static`

**GetImage**(**element**: [IStiAppComponent](../root/IStiAppComponent.md), **size**: Size, **mapData**: Hashtable, **elementKey**: string, **ignoreSize**: bool): byte[]

**Parameters**

- **element** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **size** (Size)  
- **mapData** (Hashtable)  
- **elementKey** (string)  
- **ignoreSize** (bool)  

**Returns** byte[]

---

**GetImage**(**size**: Size, **userBingKey**: string, **pushPins**: List<string>, **provider**: [StiGeoMapProviderType](../Gis/StiGeoMapProviderType.md), **onePointZoom**: int): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **size** (Size)  
- **userBingKey** (string)  
- **pushPins** (List<string>)  
- **provider** ([StiGeoMapProviderType](../Gis/StiGeoMapProviderType.md))  
- **onePointZoom** (int)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### GetScript `static`

**GetScript**(**element**: [IStiAppComponent](../root/IStiAppComponent.md), **mapData**: Hashtable): string

**Parameters**

- **element** ([IStiAppComponent](../root/IStiAppComponent.md))  
- **mapData** (Hashtable)  

**Returns** string


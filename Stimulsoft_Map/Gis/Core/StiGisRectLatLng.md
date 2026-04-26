---
title: "StiGisRectLatLng Struct"
---

## StiGisRectLatLng Struct

**Namespace:** `Stimulsoft.Map.Gis.Core`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisRectLatLng**([StiGisPointLatLng](StiGisPointLatLng.md) location, [StiGisSizeLatLng](StiGisSizeLatLng.md) size) |  |
| **StiGisRectLatLng**(double lat, double lng, double widthLng, double heightLat) |  |

**StiGisRectLatLng**(**location**: [StiGisPointLatLng](StiGisPointLatLng.md), **size**: [StiGisSizeLatLng](StiGisSizeLatLng.md))

**Parameters**

- **location** ([StiGisPointLatLng](StiGisPointLatLng.md))  
- **size** ([StiGisSizeLatLng](StiGisSizeLatLng.md))  

---

**StiGisRectLatLng**(**lat**: double, **lng**: double, **widthLng**: double, **heightLat**: double)

**Parameters**

- **lat** (double)  
- **lng** (double)  
- **widthLng** (double)  
- **heightLat** (double)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HeightLat** | double |  |
| **Lat** | double |  |
| **Lng** | double |  |
| **WidthLng** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Contains** *(+1 overloads)* | bool |  |
| **Equals** | bool |  |
| **FromLTRB** `static` | [StiGisRectLatLng](StiGisRectLatLng.md) |  |
| **GetHashCode** | int |  |
| **ToString** | string |  |

---

### Method Details

#### Contains

**Contains**(**lat**: double, **lng**: double): bool

**Parameters**

- **lat** (double)  
- **lng** (double)  

**Returns** bool

---

**Contains**(**pt**: [StiGisPointLatLng](StiGisPointLatLng.md)): bool

**Parameters**

- **pt** ([StiGisPointLatLng](StiGisPointLatLng.md))  

**Returns** bool


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### FromLTRB `static`

**FromLTRB**(**leftLng**: double, **topLat**: double, **rightLng**: double, **bottomLat**: double): [StiGisRectLatLng](StiGisRectLatLng.md)

**Parameters**

- **leftLng** (double)  
- **topLat** (double)  
- **rightLng** (double)  
- **bottomLat** (double)  

**Returns** [StiGisRectLatLng](StiGisRectLatLng.md)


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiGisRectLatLng](StiGisRectLatLng.md) |  |

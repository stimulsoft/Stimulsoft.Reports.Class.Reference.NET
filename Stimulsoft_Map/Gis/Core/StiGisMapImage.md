---
title: "StiGisMapImage Class"
---

## StiGisMapImage Class

**Namespace:** `Stimulsoft.Map.Gis.Core`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisMapImage**(bytedata ) |  |

**StiGisMapImage**(****: bytedata)

**Parameters**

- **** (bytedata)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **FromByteArray** `static` | [StiGisMapImage](StiGisMapImage.md) |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### FromByteArray `static`

**FromByteArray**(****: bytebuffer, **mode**: [StiGeoRenderMode](StiGeoRenderMode.md)): [StiGisMapImage](StiGisMapImage.md)

**Parameters**

- **** (bytebuffer)  
- **mode** ([StiGeoRenderMode](StiGeoRenderMode.md))  

**Returns** [StiGisMapImage](StiGisMapImage.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **BitmapGdi** | [Image](../../../Stimulsoft_Drawing/root/Image.md) |  |
| **Data** | byte[] |  |

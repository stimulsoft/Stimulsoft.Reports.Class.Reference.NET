---
title: "StiGisMapProvider Class"
---

## StiGisMapProvider Class

**Namespace:** `Stimulsoft.Map.Gis.Providers`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisMapProvider**() |  |

**StiGisMapProvider**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsInitialized** | bool |  |
| **ProviderType** | [StiGeoMapProviderType](../../../Stimulsoft_Base/Gis/StiGeoMapProviderType.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckTileImageHttpResponse** | bool |  |
| **Equals** | bool |  |
| **ForceBasicHttpAuthentication** | void |  |
| **GetContentUsingHttp** | string |  |
| **GetHashCode** | int |  |
| **GetServerNum** `static` | int |  |
| **GetTileImage** | [StiGisMapImage](../Core/StiGisMapImage.md) |  |
| **GetTileImageUsingHttp** | [StiGisMapImage](../Core/StiGisMapImage.md) |  |
| **OnInitialized** | void |  |
| **ToString** | string |  |

---

### Method Details

#### CheckTileImageHttpResponse

**CheckTileImageHttpResponse**(**response**: WebResponse): bool

**Parameters**

- **response** (WebResponse)  

**Returns** bool


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### ForceBasicHttpAuthentication

**ForceBasicHttpAuthentication**(**userName**: string, **userPassword**: string): void

**Parameters**

- **userName** (string)  
- **userPassword** (string)  


---

#### GetContentUsingHttp

**GetContentUsingHttp**(**url**: string): string

**Parameters**

- **url** (string)  

**Returns** string


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### GetServerNum `static`

**GetServerNum**(**pos**: [StiGisPoint](../Core/StiGisPoint.md), **max**: int): int

**Parameters**

- **pos** ([StiGisPoint](../Core/StiGisPoint.md))  
- **max** (int)  

**Returns** int


---

#### GetTileImage

**GetTileImage**(**pos**: [StiGisPoint](../Core/StiGisPoint.md), **zoom**: int, **mode**: [StiGeoRenderMode](../Core/StiGeoRenderMode.md)): [StiGisMapImage](../Core/StiGisMapImage.md)

**Parameters**

- **pos** ([StiGisPoint](../Core/StiGisPoint.md))  
- **zoom** (int)  
- **mode** ([StiGeoRenderMode](../Core/StiGeoRenderMode.md))  

**Returns** [StiGisMapImage](../Core/StiGisMapImage.md)


---

#### GetTileImageUsingHttp

**GetTileImageUsingHttp**(**url**: string, **mode**: [StiGeoRenderMode](../Core/StiGeoRenderMode.md)): [StiGisMapImage](../Core/StiGisMapImage.md)

**Parameters**

- **url** (string)  
- **mode** ([StiGeoRenderMode](../Core/StiGeoRenderMode.md))  

**Returns** [StiGisMapImage](../Core/StiGisMapImage.md)


---

#### OnInitialized

**OnInitialized**(): void


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Area** | StiGisRectLatLng? |  |
| **Copyright** | string |  |
| **MinZoom** | int |  |
| **Name** | string |  |
| **RefererUrl** | string |  |
| **TimeoutMs** | int |  |

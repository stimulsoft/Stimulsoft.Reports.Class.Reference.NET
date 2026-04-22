---
title: "StiGisMapProvider Class"
---

## StiGisMapProvider Class

**Namespace:** `Stimulsoft.Map.Gis.Providers`  
**Assembly:** `Stimulsoft.Map`

```csharp
public abstract class StiGisMapProvider
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisMapProvider**() |  |

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

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Area** | StiGisRectLatLng? |  |
| **Copyright** | string |  |
| **MinZoom** | int |  |
| **Name** | string |  |
| **RefererUrl** | string |  |
| **TimeoutMs** | int |  |

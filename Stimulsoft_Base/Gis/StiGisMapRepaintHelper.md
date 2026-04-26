---
title: "StiGisMapRepaintHelper Class"
---

## StiGisMapRepaintHelper Class

**Namespace:** `Stimulsoft.Base.Gis`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateWinFormsControl** `static` | [IStiGisMapControl](IStiGisMapControl.md) |  |
| **CreateWpfControl** `static` | [IStiGisMapControl](IStiGisMapControl.md) |  |
| **FetchAllComponents** `static` | List<object> |  |
| **Get** `static` | [IStiGisMapSimpleView](IStiGisMapSimpleView.md) |  |
| **GetForExport** `static` | [IStiGisMapSimpleView](IStiGisMapSimpleView.md) |  |
| **Init** `static` | void |  |

---

### Method Details

#### CreateWinFormsControl `static`

**CreateWinFormsControl**(): [IStiGisMapControl](IStiGisMapControl.md)

**Returns** [IStiGisMapControl](IStiGisMapControl.md)


---

#### CreateWpfControl `static`

**CreateWpfControl**(**fontFamily**: object): [IStiGisMapControl](IStiGisMapControl.md)

**Parameters**

- **fontFamily** (object)  

**Returns** [IStiGisMapControl](IStiGisMapControl.md)


---

#### FetchAllComponents `static`

**FetchAllComponents**(): List<object>

**Returns** List<object>


---

#### Get `static`

**Get**(**element**: object, **provider**: [StiGeoMapProviderType](StiGeoMapProviderType.md), **data**: [StiGisMapData](StiGisMapData.md)): [IStiGisMapSimpleView](IStiGisMapSimpleView.md)

**Parameters**

- **element** (object)  
- **provider** ([StiGeoMapProviderType](StiGeoMapProviderType.md))  
- **data** ([StiGisMapData](StiGisMapData.md))  

**Returns** [IStiGisMapSimpleView](IStiGisMapSimpleView.md)


---

#### GetForExport `static`

**GetForExport**(**provider**: [StiGeoMapProviderType](StiGeoMapProviderType.md), **data**: [StiGisMapData](StiGisMapData.md)): [IStiGisMapSimpleView](IStiGisMapSimpleView.md)

**Parameters**

- **provider** ([StiGeoMapProviderType](StiGeoMapProviderType.md))  
- **data** ([StiGisMapData](StiGisMapData.md))  

**Returns** [IStiGisMapSimpleView](IStiGisMapSimpleView.md)


---

#### Init `static`

**Init**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Tick** | EventHandler |  |

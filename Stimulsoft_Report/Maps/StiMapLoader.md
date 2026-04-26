---
title: "StiMapLoader Class"
---

## StiMapLoader Class

**Namespace:** `Stimulsoft.Report.Maps`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsMapAssemblyLoaded** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DeleteAllCustomMaps** `static` | void |  |
| **GetGeomsObject** `static` | [StiMapGeomsContainer](../Stimulsoft/Base/Maps/Geoms/StiMapGeomsContainer.md) |  |
| **LoadResource** `static` | [StiMapSvgContainer](StiMapSvgContainer.md) |  |
| **ParsePath** `static` | List<[StiMapGeom](../Stimulsoft/Base/Maps/Geoms/StiMapGeom.md)> |  |

---

### Method Details

#### DeleteAllCustomMaps `static`

**DeleteAllCustomMaps**(): void


---

#### GetGeomsObject `static`

**GetGeomsObject**(**report**: [StiReport](../root/StiReport.md), **resourceName**: string, **lang**: string): [StiMapGeomsContainer](../Stimulsoft/Base/Maps/Geoms/StiMapGeomsContainer.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **resourceName** (string)  
- **lang** (string)  

**Returns** [StiMapGeomsContainer](../Stimulsoft/Base/Maps/Geoms/StiMapGeomsContainer.md)


---

#### LoadResource `static`

**LoadResource**(**report**: [StiReport](../root/StiReport.md), **resourceName**: string, **lang**: string): [StiMapSvgContainer](StiMapSvgContainer.md)

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **resourceName** (string)  
- **lang** (string)  

**Returns** [StiMapSvgContainer](StiMapSvgContainer.md)


---

#### ParsePath `static`

**ParsePath**(**text**: string): List<[StiMapGeom](../Stimulsoft/Base/Maps/Geoms/StiMapGeom.md)>

**Parameters**

- **text** (string)  

**Returns** List<[StiMapGeom](../Stimulsoft/Base/Maps/Geoms/StiMapGeom.md)>


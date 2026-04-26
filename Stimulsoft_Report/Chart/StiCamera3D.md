---
title: "StiCamera3D Class"
---

## StiCamera3D Class

**Namespace:** `Stimulsoft.Report.Chart`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCamera3D**([StiRender3D](StiRender3D.md) render, [StiVector3](StiVector3.md) point) |  |

**StiCamera3D**(**render**: [StiRender3D](StiRender3D.md), **point**: [StiVector3](StiVector3.md))

**Parameters**

- **render** ([StiRender3D](StiRender3D.md))  
- **point** ([StiVector3](StiVector3.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Position** | [StiVector4](StiVector4.md) |  |
| **Render** | [StiRender3D](StiRender3D.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CameraMatrix** | [StiMatrix](../Export/StiMatrix.md) |  |
| **RotateMatrix** | [StiMatrix](../Export/StiMatrix.md) |  |
| **TranslateMatrix** | [StiMatrix](../Export/StiMatrix.md) |  |

---

### Method Details

#### CameraMatrix

**CameraMatrix**(): [StiMatrix](../Export/StiMatrix.md)

**Returns** [StiMatrix](../Export/StiMatrix.md)


---

#### RotateMatrix

**RotateMatrix**(): [StiMatrix](../Export/StiMatrix.md)

**Returns** [StiMatrix](../Export/StiMatrix.md)


---

#### TranslateMatrix

**TranslateMatrix**(): [StiMatrix](../Export/StiMatrix.md)

**Returns** [StiMatrix](../Export/StiMatrix.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **FarPlane** | double |  |
| **NearPlane** | double |  |
| **h_fov** | double |  |
| **v_fov** | double |  |

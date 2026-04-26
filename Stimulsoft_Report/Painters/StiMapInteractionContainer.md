---
title: "StiMapInteractionContainer Class"
---

## StiMapInteractionContainer Class

**Namespace:** `Stimulsoft.Report.Painters`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiMapInteractionContainer**(Dictionary<string, [StiMapSvg](../Maps/StiMapSvg.md)> hashPaths, double mapGeomWidth, double mapGeomHeight) |  |

**StiMapInteractionContainer**(**hashPaths**: Dictionary<string, [StiMapSvg](../Maps/StiMapSvg.md)>, **mapGeomWidth**: double, **mapGeomHeight**: double)

**Parameters**

- **hashPaths** (Dictionary<string, [StiMapSvg](../Maps/StiMapSvg.md)>)  
- **mapGeomWidth** (double)  
- **mapGeomHeight** (double)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Zoom** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **Dispose** | void |  |
| **GetKeyByPosition** | string |  |
| **GetMapSvgByPosition** | [StiMapSvg](../Maps/StiMapSvg.md) |  |
| **SetValue** | void |  |

---

### Method Details

#### Add

**Add**(**key**: string, **path**: List<[GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)>): void

**Parameters**

- **key** (string)  
- **path** (List<[GraphicsPath](../../Stimulsoft_Drawing/Drawing2D/GraphicsPath.md)>)  


---

#### Dispose

**Dispose**(): void


---

#### GetKeyByPosition

**GetKeyByPosition**(**pos**: Point, **zoom**: float, **globalMovePoint**: Point, **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): string

**Parameters**

- **pos** (Point)  
- **zoom** (float)  
- **globalMovePoint** (Point)  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** string


---

#### GetMapSvgByPosition

**GetMapSvgByPosition**(**pos**: Point): [StiMapSvg](../Maps/StiMapSvg.md)

**Parameters**

- **pos** (Point)  

**Returns** [StiMapSvg](../Maps/StiMapSvg.md)


---

#### SetValue

**SetValue**(**key**: string, **value**: string): void

**Parameters**

- **key** (string)  
- **value** (string)  


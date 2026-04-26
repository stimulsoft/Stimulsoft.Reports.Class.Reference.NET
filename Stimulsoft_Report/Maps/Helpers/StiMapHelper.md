---
title: "StiMapHelper Class"
---

## StiMapHelper Class

**Namespace:** `Stimulsoft.Report.Maps.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Allow3D** `static` *(+1 overloads)* | bool |  |
| **GetColors** `static` | Color[] |  |
| **GetMapSample** `static` | StiMap |  |
| **GetStates** `static` | string[] |  |
| **IsAfrica** `static` | bool |  |
| **IsAsia** `static` | bool |  |
| **IsEU** `static` | bool |  |
| **IsNorthAmerica** `static` | bool |  |
| **IsOceania** `static` | bool |  |
| **IsSouthAmerica** `static` | bool |  |
| **IsWorld** `static` | bool |  |
| **PrepareIsoCode** `static` | string |  |

---

### Method Details

#### Allow3D `static`

**Allow3D**(**mapID**: string): bool

**Parameters**

- **mapID** (string)  

**Returns** bool

---

**Allow3D**(**mapID**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **mapID** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### GetColors `static`

**GetColors**(): Color[]

**Returns** Color[]


---

#### GetMapSample `static`

**GetMapSample**(**baseReport**: [StiReport](../../root/StiReport.md), **mapID**: string): StiMap

**Parameters**

- **baseReport** ([StiReport](../../root/StiReport.md))  
- **mapID** (string)  

**Returns** StiMap


---

#### GetStates `static`

**GetStates**(**report**: [StiReport](../../root/StiReport.md), **id**: string, **lang**: string): string[]

**Parameters**

- **report** ([StiReport](../../root/StiReport.md))  
- **id** (string)  
- **lang** (string)  

**Returns** string[]


---

#### IsAfrica `static`

**IsAfrica**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsAsia `static`

**IsAsia**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsEU `static`

**IsEU**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsNorthAmerica `static`

**IsNorthAmerica**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsOceania `static`

**IsOceania**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsSouthAmerica `static`

**IsSouthAmerica**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### IsWorld `static`

**IsWorld**(**id**: [StiMapID](../StiMapID.md)): bool

**Parameters**

- **id** ([StiMapID](../StiMapID.md))  

**Returns** bool


---

#### PrepareIsoCode `static`

**PrepareIsoCode**(**text**: string): string

**Parameters**

- **text** (string)  

**Returns** string


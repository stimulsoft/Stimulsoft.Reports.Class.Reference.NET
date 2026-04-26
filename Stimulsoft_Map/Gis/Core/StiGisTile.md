---
title: "StiGisTile Struct"
---

## StiGisTile Struct

**Namespace:** `Stimulsoft.Map.Gis.Core`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGisTile**(int zoom, [StiGisPoint](StiGisPoint.md) pos) |  |

**StiGisTile**(**zoom**: int, **pos**: [StiGisPoint](StiGisPoint.md))

**Parameters**

- **zoom** (int)  
- **pos** ([StiGisPoint](StiGisPoint.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Pos** | [StiGisPoint](StiGisPoint.md) |  |
| **Zoom** | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **Equals** | bool |  |
| **GetHashCode** | int |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Empty** | [StiGisTile](StiGisTile.md) |  |
| **Image** | [StiGisMapImage](StiGisMapImage.md) |  |
| **NotEmpty** | bool |  |

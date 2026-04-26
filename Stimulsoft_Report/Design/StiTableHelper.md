---
title: "StiTableHelper Class"
---

## StiTableHelper Class

**Namespace:** `Stimulsoft.Report.Design`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableHelper**([IStiDesignerBase](IStiDesignerBase.md) designer, bool altKeyMode) |  |

**StiTableHelper**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **altKeyMode**: bool)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **altKeyMode** (bool)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetDistForResize** `static` | decimal |  |
| **GetSelectedCount** `static` | int |  |
| **GetSelectedLines** `static` | void |  |
| **GetSelectedRectangle** `static` *(+4 overloads)* | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **IsAllowUseInTableMode** `static` | bool |  |
| **IsTableMode** `static` *(+1 overloads)* | bool |  |
| **ProcessResizeColumns** | void |  |
| **ProcessResizeRows** | void |  |
| **ProcessResizeTable** | void |  |
| **ResizeColumns** | void |  |
| **ResizeRows** | void |  |
| **RestoreComponentLocation** | void |  |
| **RestoreComponentsLocation** | void |  |
| **SaveComponentLocation** | void |  |
| **SaveComponentsLocation** | void |  |
| **SaveCursorLocation** | void |  |
| **SaveSelectedRectangle** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### GetDistForResize `static`

**GetDistForResize**(**comp**: StiComponent): decimal

**Parameters**

- **comp** (StiComponent)  

**Returns** decimal


---

#### GetSelectedCount `static`

**GetSelectedCount**(**comps**: StiComponentsCollection): int

**Parameters**

- **comps** (StiComponentsCollection)  

**Returns** int


---

#### GetSelectedLines `static`

**GetSelectedLines**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **xx**: Hashtable, **yy**: Hashtable, **isPaint**: bool): void

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **xx** (Hashtable)  
- **yy** (Hashtable)  
- **isPaint** (bool)  


---

#### GetSelectedRectangle `static`

**GetSelectedRectangle**(**designer**: [IStiDesignerBase](IStiDesignerBase.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

---

**GetSelectedRectangle**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **isPaintRect**: bool): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **isPaintRect** (bool)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

---

**GetSelectedRectangle**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **isPaintRect**: bool, **useZoom**: bool): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **isPaintRect** (bool)  
- **useZoom** (bool)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

---

**GetSelectedRectangle**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **isPaintRect**: bool, **comps**: StiComponentsCollection): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **isPaintRect** (bool)  
- **comps** (StiComponentsCollection)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

---

**GetSelectedRectangle**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **isPaintRect**: bool, **useZoom**: bool, **comps**: StiComponentsCollection): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **isPaintRect** (bool)  
- **useZoom** (bool)  
- **comps** (StiComponentsCollection)  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)


---

#### IsAllowUseInTableMode `static`

**IsAllowUseInTableMode**(**comp**: StiComponent): bool

**Parameters**

- **comp** (StiComponent)  

**Returns** bool


---

#### IsTableMode `static`

**IsTableMode**(**component**: StiComponent): bool

**Parameters**

- **component** (StiComponent)  

**Returns** bool

---

**IsTableMode**(**designer**: [IStiDesignerBase](IStiDesignerBase.md)): bool

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  

**Returns** bool


---

#### ProcessResizeColumns

**ProcessResizeColumns**(): void


---

#### ProcessResizeRows

**ProcessResizeRows**(): void


---

#### ProcessResizeTable

**ProcessResizeTable**(**resizeHorizontally**: bool, **resizeVertically**: bool): void

**Parameters**

- **resizeHorizontally** (bool)  
- **resizeVertically** (bool)  


---

#### ResizeColumns

**ResizeColumns**(**lineX**: decimal, **offset**: double, **resizeType**: [StiResizeType](StiResizeType.md)): void

**Parameters**

- **lineX** (decimal)  
- **offset** (double)  
- **resizeType** ([StiResizeType](StiResizeType.md))  


---

#### ResizeRows

**ResizeRows**(**lineY**: decimal, **offset**: double, **resizeType**: [StiResizeType](StiResizeType.md)): void

**Parameters**

- **lineY** (decimal)  
- **offset** (double)  
- **resizeType** ([StiResizeType](StiResizeType.md))  


---

#### RestoreComponentLocation

**RestoreComponentLocation**(**comp**: StiComponent): void

**Parameters**

- **comp** (StiComponent)  


---

#### RestoreComponentsLocation

**RestoreComponentsLocation**(): void


---

#### SaveComponentLocation

**SaveComponentLocation**(**component**: StiComponent): void

**Parameters**

- **component** (StiComponent)  


---

#### SaveComponentsLocation

**SaveComponentsLocation**(): void


---

#### SaveCursorLocation

**SaveCursorLocation**(**eX**: int, **eY**: int): void

**Parameters**

- **eX** (int)  
- **eY** (int)  


---

#### SaveSelectedRectangle

**SaveSelectedRectangle**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **IsControlKeyPressed** | bool |  |

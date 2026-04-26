---
title: "StiTableHelperV2 Class"
---

## StiTableHelperV2 Class

**Namespace:** `Stimulsoft.Report.Design`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableHelperV2**([IStiDesignerBase](IStiDesignerBase.md) designer, bool altKeyMode) |  |

**StiTableHelperV2**(**designer**: [IStiDesignerBase](IStiDesignerBase.md), **altKeyMode**: bool)

**Parameters**

- **designer** ([IStiDesignerBase](IStiDesignerBase.md))  
- **altKeyMode** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SelectedCell** | [IStiTableCell](../Components/Table/IStiTableCell.md) |  |
| **SelectedTable** | StiTable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void |  |
| **GetDistForResize** `static` | double |  |
| **GetSelectedRectangle** `static` *(+4 overloads)* | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) |  |
| **IsAllowUseInTableMode** `static` | bool |  |
| **ProcessResizeCell** | void |  |
| **ProcessResizeTable** | void |  |
| **ResizeCell** | void |  |
| **ResizeColumns** | bool |  |
| **ResizeRows** | bool |  |
| **RestoreComponentLocation** | void |  |
| **RestoreComponentsLocation** *(+1 overloads)* | void |  |
| **SaveComponentsLocation** | void |  |
| **SaveCursorLocation** | void |  |
| **SaveSelectedRectangle** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void


---

#### GetDistForResize `static`

**GetDistForResize**(**comp**: StiComponent): double

**Parameters**

- **comp** (StiComponent)  

**Returns** double


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

#### ProcessResizeCell

**ProcessResizeCell**(): void


---

#### ProcessResizeTable

**ProcessResizeTable**(**resizeHorizontally**: bool, **resizeVertically**: bool): void

**Parameters**

- **resizeHorizontally** (bool)  
- **resizeVertically** (bool)  


---

#### ResizeCell

**ResizeCell**(**offsetX**: double, **offsetY**: double): void

**Parameters**

- **offsetX** (double)  
- **offsetY** (double)  


---

#### ResizeColumns

**ResizeColumns**(**baseCell**: StiComponent, **lineX**: double, **offset**: double, **action**: [StiAction](../../Stimulsoft_Report_Check/root/StiAction.md), **changedComponentList**: Dictionary<StiComponent, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)>): bool

**Parameters**

- **baseCell** (StiComponent)  
- **lineX** (double)  
- **offset** (double)  
- **action** ([StiAction](../../Stimulsoft_Report_Check/root/StiAction.md))  
- **changedComponentList** (Dictionary<StiComponent, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)>)  

**Returns** bool


---

#### ResizeRows

**ResizeRows**(**baseCell**: StiComponent, **lineY**: double, **offset**: double, **action**: [StiAction](../../Stimulsoft_Report_Check/root/StiAction.md), **changedComponentList**: Dictionary<StiComponent, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)>): bool

**Parameters**

- **baseCell** (StiComponent)  
- **lineY** (double)  
- **offset** (double)  
- **action** ([StiAction](../../Stimulsoft_Report_Check/root/StiAction.md))  
- **changedComponentList** (Dictionary<StiComponent, [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)>)  

**Returns** bool


---

#### RestoreComponentLocation

**RestoreComponentLocation**(**comp**: StiComponent): void

**Parameters**

- **comp** (StiComponent)  


---

#### RestoreComponentsLocation

**RestoreComponentsLocation**(): void

---

**RestoreComponentsLocation**(**table**: StiTable): void

**Parameters**

- **table** (StiTable)  


---

#### SaveComponentsLocation

**SaveComponentsLocation**(**table**: StiTable): void

**Parameters**

- **table** (StiTable)  


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
| **IsAnySelected** | bool |  |
| **IsSelectedCell** | bool |  |
| **IsSelectedTable** | bool |  |

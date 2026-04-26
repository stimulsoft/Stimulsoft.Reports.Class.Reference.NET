---
title: "StiCrossDataBandV1Builder Class"
---

## StiCrossDataBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiDataBandV1Builder](StiDataBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckFreeSpace** | bool |  |
| **DecFreeSpace** | void |  |
| **GetDataIsPrepared** | bool |  |
| **GetFreeSpaceFromComponent** | double |  |
| **GetFreeSpaceFromRectangle** | double |  |
| **IncFreeSpace** | void |  |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **MoveNext** | void | Moves on the next row. |
| **Prepare** | void | Prepares a component for rendering. |
| **SetDataIsPrepared** | void |  |
| **SetReportVariables** | void |  |

---

### Method Details

#### CheckFreeSpace

**CheckFreeSpace**(**masterDataBand**: StiDataBand, **outContainer**: StiContainer): bool

**Parameters**

- **masterDataBand** (StiDataBand)  
- **outContainer** (StiContainer)  

**Returns** bool


---

#### DecFreeSpace

**DecFreeSpace**(**masterDataBand**: StiDataBand, **component**: StiComponent): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **component** (StiComponent)  


---

#### GetDataIsPrepared

**GetDataIsPrepared**(**masterDataBand**: StiDataBand): bool

**Parameters**

- **masterDataBand** (StiDataBand)  

**Returns** bool


---

#### GetFreeSpaceFromComponent

**GetFreeSpaceFromComponent**(**component**: StiComponent): double

**Parameters**

- **component** (StiComponent)  

**Returns** double


---

#### GetFreeSpaceFromRectangle

**GetFreeSpaceFromRectangle**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): double

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  

**Returns** double


---

#### IncFreeSpace

**IncFreeSpace**(**masterDataBand**: StiDataBand, **component**: StiComponent): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **component** (StiComponent)  


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A rendered component.  
- **outContainer** (StiContainer) — A panel in what rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### MoveNext

**MoveNext**(**masterDataBand**: StiDataBand): void

Moves on the next row.

**Parameters**

- **masterDataBand** (StiDataBand)  


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### SetDataIsPrepared

**SetDataIsPrepared**(**masterDataBand**: StiDataBand, **value**: bool): void

**Parameters**

- **masterDataBand** (StiDataBand)  
- **value** (bool)  


---

#### SetReportVariables

**SetReportVariables**(**masterDataBand**: StiDataBand): void

**Parameters**

- **masterDataBand** (StiDataBand)  


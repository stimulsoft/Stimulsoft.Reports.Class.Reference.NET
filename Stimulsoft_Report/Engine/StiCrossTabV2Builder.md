---
title: "StiCrossTabV2Builder Class"
---

## StiCrossTabV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiContainerV2Builder](StiContainerV2Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCollapsingName** `static` *(+1 overloads)* | string |  |
| **InternalRender** | StiComponent |  |
| **IsCollapsed** `static` *(+1 overloads)* | bool |  |
| **Prepare** | void |  |
| **RenderCrossTab** | StiComponent |  |
| **RenderCrossTabOnDataBand** | StiComponent |  |
| **RenderCrossTabUnlimitedBreakable** | void |  |
| **SetCollapsed** `static` | void |  |
| **UnPrepare** | void |  |

---

### Method Details

#### GetCollapsingName `static`

**GetCollapsingName**(**header**: StiCrossHeader): string

**Parameters**

- **header** (StiCrossHeader)  

**Returns** string

---

**GetCollapsingName**(**componentName**: string, **level**: int, **value**: string): string

**Parameters**

- **componentName** (string)  
- **level** (int)  
- **value** (string)  

**Returns** string


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent): StiComponent

**Parameters**

- **masterComp** (StiComponent)  

**Returns** StiComponent


---

#### IsCollapsed `static`

**IsCollapsed**(**masterHeader**: StiCrossHeader): bool

**Parameters**

- **masterHeader** (StiCrossHeader)  

**Returns** bool

---

**IsCollapsed**(**masterHeader**: StiCrossHeader, **level**: int, **textValue**: string): bool

**Parameters**

- **masterHeader** (StiCrossHeader)  
- **level** (int)  
- **textValue** (string)  

**Returns** bool


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

**Parameters**

- **masterComp** (StiComponent)  


---

#### RenderCrossTab

**RenderCrossTab**(**pars**: [StiCrossTabParams](../CrossTab/StiCrossTabParams.md), **master**: StiCrossTab): StiComponent

**Parameters**

- **pars** ([StiCrossTabParams](../CrossTab/StiCrossTabParams.md))  
- **master** (StiCrossTab)  

**Returns** StiComponent


---

#### RenderCrossTabOnDataBand

**RenderCrossTabOnDataBand**(**pars**: [StiCrossTabParams](../CrossTab/StiCrossTabParams.md), **master**: StiCrossTab, **destination**: StiContainer, **rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)): StiComponent

**Parameters**

- **pars** ([StiCrossTabParams](../CrossTab/StiCrossTabParams.md))  
- **master** (StiCrossTab)  
- **destination** (StiContainer)  
- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md))  

**Returns** StiComponent


---

#### RenderCrossTabUnlimitedBreakable

**RenderCrossTabUnlimitedBreakable**(**pars**: [StiCrossTabParams](../CrossTab/StiCrossTabParams.md), **master**: StiCrossTab, **destination**: StiContainer, **rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)): void

**Parameters**

- **pars** ([StiCrossTabParams](../CrossTab/StiCrossTabParams.md))  
- **master** (StiCrossTab)  
- **destination** (StiContainer)  
- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md))  


---

#### SetCollapsed `static`

**SetCollapsed**(**masterHeader**: StiCrossHeader, **isCollapsed**: bool): void

**Parameters**

- **masterHeader** (StiCrossHeader)  
- **isCollapsed** (bool)  


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

**Parameters**

- **masterComp** (StiComponent)  


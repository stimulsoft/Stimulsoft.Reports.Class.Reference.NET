---
title: "StiPivotTableContainer Class"
---

## StiPivotTableContainer Class

**Namespace:** `Stimulsoft.Dashboard.Drawing.Painters.PivotTable`

### Inheritance

Implements: [IStiPivotGridContainer](../../../Stimulsoft_Report/Dashboard/IStiPivotGridContainer.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPivotTableContainer**(Control control, StiPivotTableElement element) |  |

**StiPivotTableContainer**(**control**: Control, **element**: StiPivotTableElement)

**Parameters**

- **control** (Control)  
- **element** (StiPivotTableElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | Control |  |
| **HeaderHeight** | int |  |
| **HeaderWidth** | int |  |
| **Height** | double |  |
| **OnlySummaries** | bool |  |
| **Width** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **ExpandCollapse** | void |  |
| **FindSelectableCell** | [StiPivotTableCell](StiPivotTableCell.md) |  |
| **GetParent** | [StiPivotTableCell](StiPivotTableCell.md) |  |
| **GridPaint** | void |  |
| **MakeGrid** | void |  |
| **OnMouseMove** | void |  |
| **OpenLink** | void |  |
| **OpenNewTab** | void |  |
| **RestoreState** | void |  |
| **SaveState** | void |  |
| **UpdateSize** | void |  |
| **UpdateWidthAndHeight** | void |  |

---

### Method Details

#### Clear

**Clear**(): void


---

#### ExpandCollapse

**ExpandCollapse**(**expand**: bool): void

**Parameters**

- **expand** (bool)  


---

#### FindSelectableCell

**FindSelectableCell**(**cell**: [StiPivotTableCell](StiPivotTableCell.md), **key**: Keys): [StiPivotTableCell](StiPivotTableCell.md)

**Parameters**

- **cell** ([StiPivotTableCell](StiPivotTableCell.md))  
- **key** (Keys)  

**Returns** [StiPivotTableCell](StiPivotTableCell.md)


---

#### GetParent

**GetParent**(**cell**: [StiPivotTableCell](StiPivotTableCell.md)): [StiPivotTableCell](StiPivotTableCell.md)

**Parameters**

- **cell** ([StiPivotTableCell](StiPivotTableCell.md))  

**Returns** [StiPivotTableCell](StiPivotTableCell.md)


---

#### GridPaint

**GridPaint**(**e**: PaintEventArgs, **style**: [StiPivotElementStyle](../../../Stimulsoft_Report/Dashboard/Styles/StiPivotElementStyle.md), **scrollLeft**: int, **scrollTop**: int, **isDesigner**: bool, **transformation**: Size?, **content**: bool): void

**Parameters**

- **e** (PaintEventArgs)  
- **style** ([StiPivotElementStyle](../../../Stimulsoft_Report/Dashboard/Styles/StiPivotElementStyle.md))  
- **scrollLeft** (int)  
- **scrollTop** (int)  
- **isDesigner** (bool)  
- **transformation** (Size?)  
- **content** (bool)  


---

#### MakeGrid

**MakeGrid**(**cross**: [StiCross](../../../Stimulsoft_Report/CrossTab/Core/StiCross.md), **pivot**: StiPivotTableElement): void

**Parameters**

- **cross** ([StiCross](../../../Stimulsoft_Report/CrossTab/Core/StiCross.md))  
- **pivot** (StiPivotTableElement)  


---

#### OnMouseMove

**OnMouseMove**(**x**: int, **y**: int): void

**Parameters**

- **x** (int)  
- **y** (int)  


---

#### OpenLink

**OpenLink**(**args**: StiValueEventArgs): void

**Parameters**

- **args** (StiValueEventArgs)  


---

#### OpenNewTab

**OpenNewTab**(**args**: StiValueEventArgs): void

**Parameters**

- **args** (StiValueEventArgs)  


---

#### RestoreState

**RestoreState**(): void


---

#### SaveState

**SaveState**(): void


---

#### UpdateSize

**UpdateSize**(): void


---

#### UpdateWidthAndHeight

**UpdateWidthAndHeight**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **AfterSizeUpdate** | EventHandler |  |
| **NewTab** | StiValueEventHandler |  |
| **OpenLinkHandler** | StiValueEventHandler |  |
| **TooltipHandler** | StiPivotTableElementTooltipEvenHandler |  |

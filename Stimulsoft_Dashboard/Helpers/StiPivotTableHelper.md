---
title: "StiPivotTableHelper Class"
---

## StiPivotTableHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class contains methods for working with the pivot-table element.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **SummaryTypes** `static` | Hashtable |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyStyle** `static` | void |  |
| **BuildCross** `static` | void |  |
| **ConvertToCrossTab** `static` | StiCrossTab |  |
| **GetHeadersBounds** `static` | Rectangle |  |
| **GetSummaryTypes** `static` | Hashtable |  |
| **GetViewerData** `static` | Hashtable |  |

---

### Method Details

#### ApplyStyle `static`

**ApplyStyle**(**pivot**: StiPivotTableElement, **crossTab**: StiCrossTab, **exportDataOnly**: bool, **scaleFactor**: double): void

**Parameters**

- **pivot** (StiPivotTableElement)  
- **crossTab** (StiCrossTab)  
- **exportDataOnly** (bool)  
- **scaleFactor** (double)  


---

#### BuildCross `static`

**BuildCross**(**masterCrossTab**: StiCrossTab, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **pivot**: StiPivotTableElement, **zoom**: double): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **pivot** (StiPivotTableElement)  
- **zoom** (double)  


---

#### ConvertToCrossTab `static`

**ConvertToCrossTab**(**pivot**: StiPivotTableElement, **dataTable**: [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md), **zoom**: double): StiCrossTab

**Parameters**

- **pivot** (StiPivotTableElement)  
- **dataTable** ([StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **zoom** (double)  

**Returns** StiCrossTab


---

#### GetHeadersBounds `static`

**GetHeadersBounds**(****: StiCellcells): Rectangle

**Parameters**

- **** (StiCellcells)  

**Returns** Rectangle


---

#### GetSummaryTypes `static`

**GetSummaryTypes**(): Hashtable

**Returns** Hashtable


---

#### GetViewerData `static`

**GetViewerData**(**pivotElement**: IStiPivotTableElement): Hashtable

**Parameters**

- **pivotElement** (IStiPivotTableElement)  

**Returns** Hashtable


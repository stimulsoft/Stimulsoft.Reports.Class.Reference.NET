---
title: "StiCrossTabHelper Class"
---

## StiCrossTabHelper Class

**Namespace:** `Stimulsoft.Report.CrossTab`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BuildCross** `static` | void |  |
| **BuildCrossForCrossTabDataSource** `static` | DataTable |  |
| **CalculateMaxAndMin** `static` | void |  |
| **CheckMergedRowCells** `static` | int |  |
| **ClearCross** `static` | void |  |
| **CreateCross** `static` | void |  |
| **CreateCrossForCrossTabDataSource** `static` | DataTable |  |
| **GetCellRect** `static` | [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md) |  |
| **GetCellsRect** `static` | [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md) |  |
| **GetEndCol** `static` | int |  |
| **GetEndRow** `static` | int |  |
| **IsColFieldsEmpty** `static` | bool |  |
| **IsRowFieldsEmpty** `static` | bool |  |
| **MakeHorAlignmentByWidth** `static` | void |  |
| **MakeRightToLeft** `static` | void |  |
| **RenderCells** `static` | void |  |

---

### Method Details

#### BuildCross `static`

**BuildCross**(**masterCrossTab**: StiCrossTab, **designTime**: bool): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **designTime** (bool)  


---

#### BuildCrossForCrossTabDataSource `static`

**BuildCrossForCrossTabDataSource**(**masterCrossTab**: StiCrossTab, **designTime**: bool): DataTable

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **designTime** (bool)  

**Returns** DataTable


---

#### CalculateMaxAndMin `static`

**CalculateMaxAndMin**(**outContainer**: StiContainer, **maxLeft**: double, **maxRight**: double, **startIndex**: int): void

**Parameters**

- **outContainer** (StiContainer)  
- **maxLeft** (double)  
- **maxRight** (double)  
- **startIndex** (int)  


---

#### CheckMergedRowCells `static`

**CheckMergedRowCells**(**masterCrossTab**: StiCrossTab, **startRow**: int, **endRow**: int, **startCol**: int, **endCol**: int): int

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **startRow** (int)  
- **endRow** (int)  
- **startCol** (int)  
- **endCol** (int)  

**Returns** int


---

#### ClearCross `static`

**ClearCross**(**masterCrossTab**: StiCrossTab): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  


---

#### CreateCross `static`

**CreateCross**(**masterCrossTab**: StiCrossTab): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  


---

#### CreateCrossForCrossTabDataSource `static`

**CreateCrossForCrossTabDataSource**(**masterCrossTab**: StiCrossTab): DataTable

**Parameters**

- **masterCrossTab** (StiCrossTab)  

**Returns** DataTable


---

#### GetCellRect `static`

**GetCellRect**(**masterCrossTab**: StiCrossTab, **colIndex**: int, **rowIndex**: int): [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **colIndex** (int)  
- **rowIndex** (int)  

**Returns** [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)


---

#### GetCellsRect `static`

**GetCellsRect**(**masterCrossTab**: StiCrossTab, **startCol**: int, **startRow**: int, **endCol**: int, **endRow**: int): [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **startCol** (int)  
- **startRow** (int)  
- **endCol** (int)  
- **endRow** (int)  

**Returns** [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)


---

#### GetEndCol `static`

**GetEndCol**(**masterCrossTab**: StiCrossTab, **startCol**: int, **rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md), **forceNoBreak**: bool): int

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **startCol** (int)  
- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md))  
- **forceNoBreak** (bool)  

**Returns** int


---

#### GetEndRow `static`

**GetEndRow**(**masterCrossTab**: StiCrossTab, **startRow**: int, **rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md), **forceNoBreak**: bool): int

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **startRow** (int)  
- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md))  
- **forceNoBreak** (bool)  

**Returns** int


---

#### IsColFieldsEmpty `static`

**IsColFieldsEmpty**(**masterCrossTab**: StiCrossTab): bool

**Parameters**

- **masterCrossTab** (StiCrossTab)  

**Returns** bool


---

#### IsRowFieldsEmpty `static`

**IsRowFieldsEmpty**(**masterCrossTab**: StiCrossTab): bool

**Parameters**

- **masterCrossTab** (StiCrossTab)  

**Returns** bool


---

#### MakeHorAlignmentByWidth `static`

**MakeHorAlignmentByWidth**(**outContainer**: StiContainer, **startIndex**: int): void

**Parameters**

- **outContainer** (StiContainer)  
- **startIndex** (int)  


---

#### MakeRightToLeft `static`

**MakeRightToLeft**(**masterCrossTab**: StiCrossTab): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  


---

#### RenderCells `static`

**RenderCells**(**masterCrossTab**: StiCrossTab, **outContainer**: StiContainer, **startCol**: int, **startRow**: int, **endCol**: int, **endRow**: int, **rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md), **colCorrection**: int): void

**Parameters**

- **masterCrossTab** (StiCrossTab)  
- **outContainer** (StiContainer)  
- **startCol** (int)  
- **startRow** (int)  
- **endCol** (int)  
- **endRow** (int)  
- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md))  
- **colCorrection** (int)  


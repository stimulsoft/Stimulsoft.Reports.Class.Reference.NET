---
title: "StiCross Class"
---

## StiCross Class

**Namespace:** `Stimulsoft.Report.CrossTab.Core`

### Inheritance

Inherits from: [StiGrid](StiGrid.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ColTitleFields** | StiComponentsCollection |  |
| **Cols** | [StiColumnCollection](StiColumnCollection.md) |  |
| **LeftCrossTitle** | [StiCrossTitle](../StiCrossTitle.md) |  |
| **RightCrossTitle** | [StiCrossTitle](../StiCrossTitle.md) |  |
| **RowTitleFields** | StiComponentsCollection |  |
| **Rows** | [StiRowCollection](StiRowCollection.md) |  |
| **SizesConverted** | bool |  |
| **SummaryContainer** | [StiSummaryContainer](StiSummaryContainer.md) |  |
| **SummaryCrossTitle** | [StiCrossTitle](../StiCrossTitle.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | bool |  |
| **Create** | void |  |
| **HasRightCrossTitle** | bool |  |

---

### Method Details

#### Clear

**Clear**(): bool

**Returns** bool


---

#### Create

**Create**(**table**: DataTable, **report**: [StiReport](../../root/StiReport.md), **direction**: [StiSummaryDirection](StiSummaryDirection.md), **emptyValue**: string): void

**Parameters**

- **table** (DataTable)  
- **report** ([StiReport](../../root/StiReport.md))  
- **direction** ([StiSummaryDirection](StiSummaryDirection.md))  
- **emptyValue** (string)  


---

#### HasRightCrossTitle

**HasRightCrossTitle**(): bool

**Returns** bool


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **EmptyField** | string |  |
| **IsColsEmpty** | bool |  |
| **IsRowsEmpty** | bool |  |
| **IsSummariesEmpty** | bool |  |

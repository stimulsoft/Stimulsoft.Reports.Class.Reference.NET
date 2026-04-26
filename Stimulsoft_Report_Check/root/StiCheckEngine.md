---
title: "StiCheckEngine Class"
---

## StiCheckEngine Class

**Namespace:** `Stimulsoft.Report.Check`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCheckEngine**() |  |

**StiCheckEngine**()


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ProgressInformation** | string |  |
| **ProgressMaximum** | double |  |
| **ProgressValue** | double |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckReport** | List<[StiCheck](StiCheck.md)> |  |
| **Compare** | int |  |

---

### Method Details

#### CheckReport

**CheckReport**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md)): List<[StiCheck](StiCheck.md)>

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  

**Returns** List<[StiCheck](StiCheck.md)>


---

#### Compare

**Compare**(**check1**: [StiCheck](StiCheck.md), **check2**: [StiCheck](StiCheck.md)): int

**Parameters**

- **check1** ([StiCheck](StiCheck.md))  
- **check2** ([StiCheck](StiCheck.md))  

**Returns** int


### Events

| Event | Type | Description |
| --- | --- | --- |
| **CheckingComponents** | EventHandler |  |
| **CheckingDataSource** | EventHandler |  |
| **CheckingDatabases** | EventHandler |  |
| **CheckingPages** | EventHandler |  |
| **CheckingRelations** | EventHandler |  |
| **CheckingUserFunctions** | EventHandler |  |
| **CheckingVariables** | EventHandler |  |
| **FinishCheckingComponents** | EventHandler |  |
| **FinishCheckingDataSource** | EventHandler |  |
| **FinishCheckingDatabases** | EventHandler |  |
| **FinishCheckingPages** | EventHandler |  |
| **FinishCheckingRelations** | EventHandler |  |
| **FinishCheckingReport** | EventHandler |  |
| **FinishCheckingUserFunctions** | EventHandler |  |
| **FinishCheckingVariables** | EventHandler |  |
| **StartCheckingComponents** | EventHandler |  |
| **StartCheckingDataSource** | EventHandler |  |
| **StartCheckingDatabases** | EventHandler |  |
| **StartCheckingPages** | EventHandler |  |
| **StartCheckingRelations** | EventHandler |  |
| **StartCheckingUserFunctions** | EventHandler |  |
| **StartCheckingVariables** | EventHandler |  |

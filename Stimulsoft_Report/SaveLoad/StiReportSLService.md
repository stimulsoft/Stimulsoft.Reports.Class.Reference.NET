---
title: "StiReportSLService Class"
---

## StiReportSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

### Inheritance

Inherits from: [StiSLService](StiSLService.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DockPagesToContainerIfUnitChanged** | void |  |
| **EnsureComponentsHavePageReference** | void |  |
| **Load** | void | Loads a report from the stream. |
| **LoadAsync** | Task | Loads asynchronously a report from the stream. |
| **RemoveNullComponentsFromForms** | void |  |
| **Save** | void | Saves report in the stream. |
| **SaveAsync** | Task | Saves asynchronously report in the stream. |

---

### Method Details

#### DockPagesToContainerIfUnitChanged

**DockPagesToContainerIfUnitChanged**(**report**: [StiReport](../root/StiReport.md), **storedReportUnit**: [StiReportUnitType](../root/StiReportUnitType.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  
- **storedReportUnit** ([StiReportUnitType](../root/StiReportUnitType.md))  


---

#### EnsureComponentsHavePageReference

**EnsureComponentsHavePageReference**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### Load

**Load**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Loads a report from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — The report in which loading will be done.  
- **stream** (Stream) — Stream to save report.  


---

#### LoadAsync

**LoadAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Loads asynchronously a report from the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — The report in which loading will be done.  
- **stream** (Stream) — Stream to save report.  

**Returns** Task


---

#### RemoveNullComponentsFromForms

**RemoveNullComponentsFromForms**(**report**: [StiReport](../root/StiReport.md)): void

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### Save

**Save**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): void

Saves report in the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report for saving.  
- **stream** (Stream) — Stream to save report.  


---

#### SaveAsync

**SaveAsync**(**report**: [StiReport](../root/StiReport.md), **stream**: Stream): Task

Saves asynchronously report in the stream.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Report for saving.  
- **stream** (Stream) — Stream to save report.  

**Returns** Task


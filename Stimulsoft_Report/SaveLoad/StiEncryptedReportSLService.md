---
title: "StiEncryptedReportSLService Class"
---

## StiEncryptedReportSLService Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that allows to save/load encrypted reports.

### Inheritance

Inherits from: [StiReportSLService](StiReportSLService.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Key** | string | Key for encryption. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetAction** | [StiSLActions](StiSLActions.md) | Returns actions available for the provider. |
| **GetFilter** | string | Returns a filter for the provider. |
| **Load** | void | Loads a report from the stream. |
| **LoadAsync** | Task | Loads asynchronously a report from the stream. |
| **Save** | void | Saves report in the stream. |
| **SaveAsync** | Task | Saves asynchronously report in the stream. |

---

### Method Details

#### GetAction

**GetAction**(): [StiSLActions](StiSLActions.md)

Returns actions available for the provider.

**Returns** [StiSLActions](StiSLActions.md) — Available actions.


---

#### GetFilter

**GetFilter**(): string

Returns a filter for the provider.

**Returns** string — String with filter.


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


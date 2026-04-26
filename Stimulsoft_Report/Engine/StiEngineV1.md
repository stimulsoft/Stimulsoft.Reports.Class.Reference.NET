---
title: "StiEngineV1 Class"
---

## StiEngineV1 Class

**Namespace:** `Stimulsoft.Report.Engine`

Summary description for StiEngineV1.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiEngineV1**([StiReport](../root/StiReport.md) report) |  |

**StiEngineV1**(**report**: [StiReport](../root/StiReport.md))

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsUsedResetPageNumber** | bool |  |
| **PageInProgress** | StiPage | Internal use only. |
| **RealPageNumber** | int | Gets or sets an index of the current page printed taking into consideration segmented pages. Number starts from 1. |
| **Report** | [StiReport](../root/StiReport.md) |  |
| **ReportPageNumbers** | Hashtable |  |
| **ReportTotalPageCounts** | Hashtable |  |
| **RequreResetPageNumber** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ProcessResetPageNumber** | void | Internal use only. |
| **ResetPageNumber** | void | Internal use only. |

---

### Method Details

#### ProcessResetPageNumber

**ProcessResetPageNumber**(**report**: [StiReport](../root/StiReport.md)): void

Internal use only.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


---

#### ResetPageNumber

**ResetPageNumber**(): void

Internal use only.


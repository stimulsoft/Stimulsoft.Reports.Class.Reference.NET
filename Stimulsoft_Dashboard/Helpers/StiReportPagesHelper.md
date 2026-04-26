---
title: "StiReportPagesHelper Class"
---

## StiReportPagesHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class helps in working with nested pages of a report. Nested pages are report pages which are used in drill-down interactions and can't be show in a viewer.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FetchAllNestedPages** `static` | List<StiPage> |  |
| **FetchAllPages** `static` | List<StiPage> |  |

---

### Method Details

#### FetchAllNestedPages `static`

**FetchAllNestedPages**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md)): List<StiPage>

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  

**Returns** List<StiPage>


---

#### FetchAllPages `static`

**FetchAllPages**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md), **skipNesting**: bool): List<StiPage>

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  
- **skipNesting** (bool)  

**Returns** List<StiPage>


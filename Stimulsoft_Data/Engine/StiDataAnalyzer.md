---
title: "StiDataAnalyzer Class"
---

## StiDataAnalyzer Class

**Namespace:** `Stimulsoft.Data.Engine`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Analyze** `static` | [StiDataTable](StiDataTable.md) | Analyzes the data based on the provided options and returns a resulting StiDataTable. |

---

### Method Details

#### Analyze `static`

**Analyze**(**options**: [StiDataAnalyzerOptions](StiDataAnalyzerOptions.md)): [StiDataTable](StiDataTable.md)

Analyzes the data based on the provided options and returns a resulting StiDataTable.

**Parameters**

- **options** ([StiDataAnalyzerOptions](StiDataAnalyzerOptions.md)) — The options to configure the data analysis process.  

**Returns** [StiDataTable](StiDataTable.md) — A StiDataTable containing the analyzed data. If no meters are provided or no tables are fetched, returns NullTable.


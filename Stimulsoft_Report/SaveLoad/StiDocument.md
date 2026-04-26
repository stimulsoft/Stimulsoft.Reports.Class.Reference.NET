---
title: "StiDocument Class"
---

## StiDocument Class

**Namespace:** `Stimulsoft.Report.SaveLoad`

Describes the class that is used for for storing a rendered report.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDocument**([StiReport](../root/StiReport.md) report) | Creates a new object of the type StiDocument. |

**StiDocument**(**report**: [StiReport](../root/StiReport.md))

Creates a new object of the type StiDocument.

**Parameters**

- **report** ([StiReport](../root/StiReport.md)) — Rendered report.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Report** | [StiReport](../root/StiReport.md) | Gets or sets the report which rendered pages are used for rendering of a document. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Pages** | [StiPagesCollection](../Components/StiPagesCollection.md) |  |
| **Styles** | StiStylesCollection |  |
| **Variables** | StiVariablesCollection |  |

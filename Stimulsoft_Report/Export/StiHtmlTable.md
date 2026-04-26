---
title: "StiHtmlTable Class"
---

## StiHtmlTable Class

**Namespace:** `Stimulsoft.Report.Export`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiHtmlTable**() |  |

**StiHtmlTable**()


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **RenderControl** | void |  |
| **StringToTitle** `static` | string |  |
| **StringToUrl** `static` | string |  |

---

### Method Details

#### RenderControl

**RenderControl**(**writer**: [StiHtmlTextWriter](StiHtmlTextWriter.md), **addPageBreaks**: bool): void

**Parameters**

- **writer** ([StiHtmlTextWriter](StiHtmlTextWriter.md))  
- **addPageBreaks** (bool)  


---

#### StringToTitle `static`

**StringToTitle**(**input**: string): string

**Parameters**

- **input** (string)  

**Returns** string


---

#### StringToUrl `static`

**StringToUrl**(**input**: string): string

**Parameters**

- **input** (string)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Align** | [StiHorAlignment](../../Stimulsoft_Base/Drawing/StiHorAlignment.md) |  |
| **BackImageUrl** | string |  |
| **Border** | StiBorder |  |
| **BorderWidth** | int |  |
| **CellPadding** | int |  |
| **CellSpacing** | int |  |
| **HorAlignKey** | string |  |
| **MarginsKey** | string |  |
| **PageBreakBeforeKey** | string |  |
| **Position** | string |  |
| **Rows** | ArrayList |  |
| **VertAlignKey** | string |  |
| **Width** | [StiHtmlUnit](StiHtmlUnit.md) |  |
| **WordwrapKey** | string |  |
| **htmlExport** | [StiHtmlExportService](StiHtmlExportService.md) |  |

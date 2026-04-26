---
title: "StiStimulsoftServerResource Class"
---

## StiStimulsoftServerResource Class

**Namespace:** `Stimulsoft.Report`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDrillDownReport** `static` | [StiReport](StiReport.md) | Gets the drill-down report with specified key from the Stimulsoft Server. |
| **GetImage** `static` | byte[] | Gets the image with specified key from the Stimulsoft Server. |
| **GetRichText** `static` | string | Gets the rich-text with specified key from the Stimulsoft Server. |
| **GetSubReport** `static` | [StiReport](StiReport.md) | Gets the sub-report with specified key from the Stimulsoft Server. |

---

### Method Details

#### GetDrillDownReport `static`

**GetDrillDownReport**(**component**: StiComponent, **key**: string): [StiReport](StiReport.md)

Gets the drill-down report with specified key from the Stimulsoft Server.

**Parameters**

- **component** (StiComponent)  
- **key** (string)  

**Returns** [StiReport](StiReport.md)


---

#### GetImage `static`

**GetImage**(**component**: StiImage, **key**: string): byte[]

Gets the image with specified key from the Stimulsoft Server.

**Parameters**

- **component** (StiImage)  
- **key** (string)  

**Returns** byte[]


---

#### GetRichText `static`

**GetRichText**(**component**: StiRichText, **key**: string): string

Gets the rich-text with specified key from the Stimulsoft Server.

**Parameters**

- **component** (StiRichText)  
- **key** (string)  

**Returns** string


---

#### GetSubReport `static`

**GetSubReport**(**component**: [StiSubReport](../Components/StiSubReport.md), **key**: string): [StiReport](StiReport.md)

Gets the sub-report with specified key from the Stimulsoft Server.

**Parameters**

- **component** ([StiSubReport](../Components/StiSubReport.md))  
- **key** (string)  

**Returns** [StiReport](StiReport.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **GetDrillDownReportDelegate** | StiGetDrillDownReportDelegate |  |
| **GetImageDelegate** | StiGetImageDelegate |  |
| **GetRichTextDelegate** | StiGetRichTextDelegate |  |
| **GetSubReportDelegate** | StiGetSubReportDelegate |  |

---
title: "StiRender Class"
---

## StiRender Class

**Namespace:** `Stimulsoft.Report.Engine`

A class helps to render a report.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRender**([StiReport](../root/StiReport.md) report) | Creates a new object of the StiRender type. |

**StiRender**(**report**: [StiReport](../root/StiReport.md))

Creates a new object of the StiRender type.

**Parameters**

- **report** ([StiReport](../root/StiReport.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **RenderStop** | long | Gets or sets amount typed component necessities for stop of rendering of a report. |
| **RenderedComponents** | long | Gets or sets amount rendered component. |
| **Report** | [StiReport](../root/StiReport.md) | Gets or sets a rendered report. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetNextPage** | StiPage | Returns the next rendered page. If more nothing to return - returns null. |
| **GetPageFromTemplate** | StiPage | Creates a new page on the base of a page of a template. |
| **NextPage** | void | Displaces the pointer on the following printed page. |

---

### Method Details

#### GetNextPage

**GetNextPage**(): StiPage

Returns the next rendered page. If more nothing to return - returns null.

**Returns** StiPage — Rendered page.


---

#### GetPageFromTemplate

**GetPageFromTemplate**(**tmpPage**: StiPage): StiPage

Creates a new page on the base of a page of a template.

**Parameters**

- **tmpPage** (StiPage)  

**Returns** StiPage


---

#### NextPage

**NextPage**(): void

Displaces the pointer on the following printed page.


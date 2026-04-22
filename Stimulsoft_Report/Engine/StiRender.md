---
title: "StiRender Class"
---

## StiRender Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

A class helps to render a report.

```csharp
public class StiRender
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRender**([StiReport](../StiReport.md) report) | Creates a new object of the StiRender type. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **RenderStop** | long | Gets or sets amount typed component necessities for stop of rendering of a report. |
| **RenderedComponents** | long | Gets or sets amount rendered component. |
| **Report** | [StiReport](../StiReport.md) | Gets or sets a rendered report. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetNextPage** | StiPage | Returns the next rendered page. If more nothing to return - returns null. |
| **GetPageFromTemplate** | StiPage | Creates a new page on the base of a page of a template. |
| **NextPage** | void | Displaces the pointer on the following printed page. |

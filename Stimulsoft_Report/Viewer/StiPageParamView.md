---
title: "StiPageParamView Class"
---

## StiPageParamView Class

**Namespace:** `Stimulsoft.Report.Viewer`  
**Assembly:** `Stimulsoft.Report`

This class is used for keeping parameter pages for preview window.

```csharp
public class StiPageParamView
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPageParamView**() | Creates a new object of the type StiPageParamView. |
| **StiPageParamView**(int x, int y, int width, int height, int line) | Creates a new object of the type StiPageParamView. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Height** | int | Gets or sets height in window of the preview. |
| **Line** | int | Gets or sets number to lines in which is placed page. |
| **Page** | StiPage | Gets or sets page, which parameters describes the object. |
| **Width** | int | Gets or sets width in window of the preview. |
| **X** | int | Gets or sets X coordinate in window of the preview. |
| **Y** | int | Gets or sets Y coordinate in window of the preview. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **DisplayRectangle** | Rectangle | Gets rectangle, which occupies the page in window of the preview. |

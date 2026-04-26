---
title: "StiPageParamView Class"
---

## StiPageParamView Class

**Namespace:** `Stimulsoft.Report.Viewer`

This class is used for keeping parameter pages for preview window.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPageParamView**() | Creates a new object of the type StiPageParamView. |
| **StiPageParamView**(int x, int y, int width, int height, int line) | Creates a new object of the type StiPageParamView. |

**StiPageParamView**()

Creates a new object of the type StiPageParamView.

---

**StiPageParamView**(**x**: int, **y**: int, **width**: int, **height**: int, **line**: int)

Creates a new object of the type StiPageParamView.

**Parameters**

- **x** (int) — X coordinate in window of the preview.  
- **y** (int) — Y coordinate in window of the preview.  
- **width** (int) — Width in window of the preview.  
- **height** (int) — Height in window of the preview.  
- **line** (int) — Number of line in which is placed page.  


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

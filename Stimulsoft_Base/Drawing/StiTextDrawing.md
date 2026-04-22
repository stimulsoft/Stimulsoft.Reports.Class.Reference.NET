---
title: "StiTextDrawing Class"
---

## StiTextDrawing Class

**Namespace:** `Stimulsoft.Base.Drawing`  
**Assembly:** `Stimulsoft.Base`

Class contains methods for text drawing.

```csharp
public class StiTextDrawing
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MeasureTrailingSpaces** `static` | bool | Gets or sets value which indicates that text drawing engine will be measure text string including trailing spaces. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BreakTextWidth** `static` | string |  |
| **CutLineLimit** `static` | string |  |
| **GetAlignment** `static` *(+1 overloads)* | StringAlignment |  |
| **GetRect** | RectangleF |  |
| **GetTexts** `static` | Word[] | Returns the collection of the words. |
| **MeasureString** `static` | SizeF |  |
| **MeasureStringWidth** `static` | SizeF | Draws the text aligned to width. |
| **SetText** | void |  |
| **SplitString** `static` | List<string> |  |
| **SplitTextWordwrap** `static` *(+1 overloads)* | List<StiTextRenderer.LineInfo> |  |
| **SplitTextWordwrapWidth** `static` | List<string> |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Count** | int |  |
| **IsEnd** | bool | Is end range. |
| **IsEnter** | bool |  |
| **IsEnter** | bool |  |
| **IsStart** | bool | Is start range. |
| **NewLineForm** | bool | After this range, new line is starting. |
| **Pos** | [PointD](PointD.md) | Position of range. |
| **Size** | [SizeD](SizeD.md) | Size of range. |
| **Start** | int |  |
| **Text** | string | Contents of range. |
| **Text** | string |  |

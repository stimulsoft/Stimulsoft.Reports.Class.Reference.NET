---
title: "StiTextDrawing Class"
---

## StiTextDrawing Class

**Namespace:** `Stimulsoft.Base.Drawing`

Class contains methods for text drawing.

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

---

### Method Details

#### BreakTextWidth `static`

**BreakTextWidth**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **rect**: [RectangleD](RectangleD.md), **stringFormat**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md), **lineHeight**: double): string

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **text** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **rect** ([RectangleD](RectangleD.md))  
- **stringFormat** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  
- **lineHeight** (double)  

**Returns** string


---

#### CutLineLimit `static`

**CutLineLimit**(**text**: string, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **rect**: [RectangleD](RectangleD.md), **textOptions**: StiTextOptions, **typographic**: bool, **isWindows**: bool): string

**Parameters**

- **text** (string)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **rect** ([RectangleD](RectangleD.md))  
- **textOptions** (StiTextOptions)  
- **typographic** (bool)  
- **isWindows** (bool)  

**Returns** string


---

#### GetAlignment `static`

**GetAlignment**(**alignment**: [StiTextHorAlignment](StiTextHorAlignment.md)): StringAlignment

**Parameters**

- **alignment** ([StiTextHorAlignment](StiTextHorAlignment.md))  

**Returns** StringAlignment

---

**GetAlignment**(**alignment**: [StiVertAlignment](StiVertAlignment.md)): StringAlignment

**Parameters**

- **alignment** ([StiVertAlignment](StiVertAlignment.md))  

**Returns** StringAlignment


---

#### GetRect

**GetRect**(**index**: int): RectangleF

**Parameters**

- **index** (int)  

**Returns** RectangleF


---

#### GetTexts `static`

**GetTexts**(**str**: string): Word[]

Returns the collection of the words.

**Parameters**

- **str** (string)  

**Returns** Word[]


---

#### MeasureString `static`

**MeasureString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): SizeF

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **text** (string)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

**Returns** SizeF


---

#### MeasureStringWidth `static`

**MeasureStringWidth**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **text**: string, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **size**: [SizeD](SizeD.md), **stringFormat**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md), **lineHeight**: double): SizeF

Draws the text aligned to width.

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md)) — Graphics to draw on.  
- **text** (string) — Text to draw on.  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md)) — Font to draw on.  
- **size** ([SizeD](SizeD.md)) — Size of rectangle to draw on.  
- **stringFormat** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md)) — Text format.  
- **lineHeight** (double)  

**Returns** SizeF


---

#### SetText

**SetText**(**st**: string): void

**Parameters**

- **st** (string)  


---

#### SplitString `static`

**SplitString**(**inputString**: string, **removeControl**: bool): List<string>

**Parameters**

- **inputString** (string)  
- **removeControl** (bool)  

**Returns** List<string>


---

#### SplitTextWordwrap `static`

**SplitTextWordwrap**(**text**: string, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **rect**: [RectangleD](RectangleD.md), **textOptions**: StiTextOptions, **ha**: [StiTextHorAlignment](StiTextHorAlignment.md), **typographic**: bool): List<StiTextRenderer.LineInfo>

**Parameters**

- **text** (string)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **rect** ([RectangleD](RectangleD.md))  
- **textOptions** (StiTextOptions)  
- **ha** ([StiTextHorAlignment](StiTextHorAlignment.md))  
- **typographic** (bool)  

**Returns** List<StiTextRenderer.LineInfo>

---

**SplitTextWordwrap**(**text**: string, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **rect**: [RectangleD](RectangleD.md), **sfBase**: [StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md), **horAlignWidth**: bool): List<StiTextRenderer.LineInfo>

**Parameters**

- **text** (string)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **rect** ([RectangleD](RectangleD.md))  
- **sfBase** ([StringFormat](../../Stimulsoft_Drawing/root/StringFormat.md))  
- **horAlignWidth** (bool)  

**Returns** List<StiTextRenderer.LineInfo>


---

#### SplitTextWordwrapWidth `static`

**SplitTextWordwrapWidth**(**text**: string, **g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **rect**: [RectangleD](RectangleD.md)): List<string>

**Parameters**

- **text** (string)  
- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **rect** ([RectangleD](RectangleD.md))  

**Returns** List<string>


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

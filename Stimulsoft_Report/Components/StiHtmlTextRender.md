---
title: "StiHtmlTextRender Class"
---

## StiHtmlTextRender Class

**Namespace:** `Stimulsoft.Report.Components`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BreakText** `static` | string |  |
| **DrawString** `static` | void |  |
| **DrawTextForOutput** `static` | void |  |
| **GetTextLines** `static` | List<string> |  |
| **MeasureString** `static` | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |

---

### Method Details

#### BreakText `static`

**BreakText**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string, **textBox**: StiText): string

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **text** (string)  
- **textBox** (StiText)  

**Returns** string


---

#### DrawString `static`

**DrawString**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string, **textBox**: StiText, **scale**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))  
- **text** (string)  
- **textBox** (StiText)  
- **scale** (double)  


---

#### DrawTextForOutput `static`

**DrawTextForOutput**(**textBox**: StiText, **outRunsList**: List<StiTextRenderer.RunInfo>, **outFontsList**: List<StiTextRenderer.StiFontState>): void

**Parameters**

- **textBox** (StiText)  
- **outRunsList** (List<StiTextRenderer.RunInfo>)  
- **outFontsList** (List<StiTextRenderer.StiFontState>)  


---

#### GetTextLines `static`

**GetTextLines**(**textBox**: StiText, **baseText**: string, **linesInfo**: List<StiTextRenderer.LineInfo>): List<string>

**Parameters**

- **textBox** (StiText)  
- **baseText** (string)  
- **linesInfo** (List<StiTextRenderer.LineInfo>)  

**Returns** List<string>


---

#### MeasureString `static`

**MeasureString**(**textBox**: StiText): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **textBox** (StiText)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


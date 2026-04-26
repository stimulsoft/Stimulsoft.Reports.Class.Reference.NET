---
title: "StiTitleMeasureHelper Class"
---

## StiTitleMeasureHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class helps in a measuring of a size of the specified title of an element.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **MeasureTitle** `static` *(+4 overloads)* | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |

---

### Method Details

#### MeasureTitle `static`

**MeasureTitle**(**title**: IStiTitle): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **title** (IStiTitle)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

---

**MeasureTitle**(**title**: IStiTitle, **zoom**: double): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **title** (IStiTitle)  
- **zoom** (double)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

---

**MeasureTitle**(**rect**: RectangleD?, **title**: IStiTitle, **titleText**: string, **zoom**: double, **maxHeight**: double): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **rect** (RectangleD?)  
- **title** (IStiTitle)  
- **titleText** (string)  
- **zoom** (double)  
- **maxHeight** (double)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

---

**MeasureTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleD?, **title**: IStiTitle, **titleText**: string, **zoom**: double, **maxHeight**: double): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleD?)  
- **title** (IStiTitle)  
- **titleText** (string)  
- **zoom** (double)  
- **maxHeight** (double)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

---

**MeasureTitle**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleD?, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md), **titleText**: string): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleD?)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  
- **titleText** (string)  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


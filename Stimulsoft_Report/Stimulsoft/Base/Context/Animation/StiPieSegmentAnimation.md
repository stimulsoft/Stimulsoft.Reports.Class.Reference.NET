---
title: "StiPieSegmentAnimation Class"
---

## StiPieSegmentAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPieSegmentAnimation**(RectangleF rectFrom, RectangleF rectTo, float startAngleFrom, float endAngleFrom, float startAngleTo, float endAngleTo, TimeSpan duration, TimeSpan beginTime) |  |
| **StiPieSegmentAnimation**(RectangleF rectFrom, RectangleF rectTo, RectangleF rectDtFrom, RectangleF rectDtTo, float startAngleFrom, float endAngleFrom, float startAngleTo, float endAngleTo, TimeSpan duration, TimeSpan beginTime) |  |

**StiPieSegmentAnimation**(**rectFrom**: RectangleF, **rectTo**: RectangleF, **startAngleFrom**: float, **endAngleFrom**: float, **startAngleTo**: float, **endAngleTo**: float, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **rectFrom** (RectangleF)  
- **rectTo** (RectangleF)  
- **startAngleFrom** (float)  
- **endAngleFrom** (float)  
- **startAngleTo** (float)  
- **endAngleTo** (float)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  

---

**StiPieSegmentAnimation**(**rectFrom**: RectangleF, **rectTo**: RectangleF, **rectDtFrom**: RectangleF, **rectDtTo**: RectangleF, **startAngleFrom**: float, **endAngleFrom**: float, **startAngleTo**: float, **endAngleTo**: float, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **rectFrom** (RectangleF)  
- **rectTo** (RectangleF)  
- **rectDtFrom** (RectangleF)  
- **rectDtTo** (RectangleF)  
- **startAngleFrom** (float)  
- **endAngleFrom** (float)  
- **startAngleTo** (float)  
- **endAngleTo** (float)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EndAngleFrom** | float |  |
| **EndAngleTo** | float |  |
| **RectDtFrom** | RectangleF |  |
| **RectDtTo** | RectangleF |  |
| **RectFrom** | RectangleF |  |
| **RectTo** | RectangleF |  |
| **StartAngleFrom** | float |  |
| **StartAngleTo** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyPreviousAnimation** | void |  |
| **IsAnimationChangingValues** `static` *(+1 overloads)* | bool |  |

---

### Method Details

#### ApplyPreviousAnimation

**ApplyPreviousAnimation**(**previousAnimations**: List<[StiAnimation](StiAnimation.md)>): void

**Parameters**

- **previousAnimations** (List<[StiAnimation](StiAnimation.md)>)  


---

#### IsAnimationChangingValues `static`

**IsAnimationChangingValues**(**series**: IStiSeries): bool

**Parameters**

- **series** (IStiSeries)  

**Returns** bool

---

**IsAnimationChangingValues**(**series**: IStiSeries, **id**: object): bool

**Parameters**

- **series** (IStiSeries)  
- **id** (object)  

**Returns** bool


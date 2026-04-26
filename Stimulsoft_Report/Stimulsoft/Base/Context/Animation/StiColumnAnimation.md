---
title: "StiColumnAnimation Class"
---

## StiColumnAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiColumnAnimation**(RectangleF rectFrom, RectangleF rectTo, TimeSpan duration, TimeSpan beginTime) |  |

**StiColumnAnimation**(**rectFrom**: RectangleF, **rectTo**: RectangleF, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **rectFrom** (RectangleF)  
- **rectTo** (RectangleF)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **RectFrom** | RectangleF |  |
| **RectTo** | RectangleF |  |

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


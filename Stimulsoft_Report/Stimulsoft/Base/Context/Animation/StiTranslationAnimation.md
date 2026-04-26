---
title: "StiTranslationAnimation Class"
---

## StiTranslationAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTranslationAnimation**(TimeSpan duration, TimeSpan beginTime) |  |
| **StiTranslationAnimation**(PointF startPoint, PointF endPoint, TimeSpan duration, TimeSpan beginTime) |  |

**StiTranslationAnimation**(**duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  

---

**StiTranslationAnimation**(**startPoint**: PointF, **endPoint**: PointF, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **startPoint** (PointF)  
- **endPoint** (PointF)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **EndPoint** | PointF |  |
| **StartPoint** | PointF |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyPreviousAnimation** | void |  |

---

### Method Details

#### ApplyPreviousAnimation

**ApplyPreviousAnimation**(**previousAnimations**: List<[StiAnimation](StiAnimation.md)>): void

**Parameters**

- **previousAnimations** (List<[StiAnimation](StiAnimation.md)>)  


---
title: "StiRotationAnimation Class"
---

## StiRotationAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRotationAnimation**(double startAngle, double endAngle, PointF centerPoint, TimeSpan duration, TimeSpan beginTime) |  |

**StiRotationAnimation**(**startAngle**: double, **endAngle**: double, **centerPoint**: PointF, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **startAngle** (double)  
- **endAngle** (double)  
- **centerPoint** (PointF)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CenterPoint** | PointF |  |
| **EndAngle** | double |  |
| **StartAngle** | double |  |

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


---
title: "StiPointsAnimation Class"
---

## StiPointsAnimation Class

**Namespace:** `Stimulsoft.Base.Context.Animation`

### Inheritance

Inherits from: [StiAnimation](StiAnimation.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPointsAnimation**(PointFpointsFrom , TimeSpan duration, TimeSpan beginTime) |  |
| **StiPointsAnimation**(PointFpointsFrom , PointFpointsTo , stringpointsIds , TimeSpan duration, TimeSpan beginTime) |  |

**StiPointsAnimation**(****: PointFpointsFrom, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **** (PointFpointsFrom)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  

---

**StiPointsAnimation**(****: PointFpointsFrom, ****: PointFpointsTo, ****: stringpointsIds, **duration**: TimeSpan, **beginTime**: TimeSpan)

**Parameters**

- **** (PointFpointsFrom)  
- **** (PointFpointsTo)  
- **** (stringpointsIds)  
- **duration** (TimeSpan)  
- **beginTime** (TimeSpan)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PointsFrom** | PointF[] |  |
| **PointsIds** | string[] |  |
| **PointsTo** | PointF[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ApplyPreviousAnimation** | void |  |
| **IsAnimationChangingValues** `static` *(+1 overloads)* | bool |  |
| **Reverse** | void |  |

---

### Method Details

#### ApplyPreviousAnimation

**ApplyPreviousAnimation**(**previousAnimations**: List<[StiAnimation](StiAnimation.md)>, **isSort**: bool): void

**Parameters**

- **previousAnimations** (List<[StiAnimation](StiAnimation.md)>)  
- **isSort** (bool)  


---

#### IsAnimationChangingValues `static`

**IsAnimationChangingValues**(**series**: IStiSeries, ****: stringpointsIds): bool

**Parameters**

- **series** (IStiSeries)  
- **** (stringpointsIds)  

**Returns** bool

---

**IsAnimationChangingValues**(**series**: IStiSeries, ****: stringpointsIds, **id**: object): bool

**Parameters**

- **series** (IStiSeries)  
- **** (stringpointsIds)  
- **id** (object)  

**Returns** bool


---

#### Reverse

**Reverse**(): void


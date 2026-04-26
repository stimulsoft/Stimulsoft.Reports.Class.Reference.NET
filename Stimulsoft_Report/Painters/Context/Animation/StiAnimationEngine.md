---
title: "StiAnimationEngine Class"
---

## StiAnimationEngine Class

**Namespace:** `Stimulsoft.Report.Painters.Context.Animation`

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AnimationExist** | bool |  |
| **IsReverse** | bool |  |
| **Speed** | double |  |
| **Tag** | object |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Continue** | void |  |
| **CorrectAnimationTimes** `static` | void |  |
| **Dispose** | void |  |
| **Finish** | void |  |
| **GetAnimationAngle** `static` *(+1 overloads)* | List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)> |  |
| **GetAnimationOpacity** `static` *(+3 overloads)* | [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md) |  |
| **GetAnimationPoint** `static` *(+1 overloads)* | PointF |  |
| **GetAnimationPoint3DY** `static` | [StiPoint3D](../../../Chart/StiPoint3D.md) |  |
| **GetAnimationPoints** `static` | PointF[] |  |
| **GetAnimationRectangle** `static` | RectangleF |  |
| **GetAnimationRectangle3D** `static` | [StiRectangle3D](../../../Chart/StiRectangle3D.md) |  |
| **GetAnimationRotation** `static` | PointF[] |  |
| **GetAnimationScale** `static` *(+2 overloads)* | RectangleF |  |
| **GetAnimationScale1** `static` | PointF[] |  |
| **GetAnimationTranslation** `static` *(+1 overloads)* | [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md) |  |
| **IsRunning** | bool |  |
| **RegisterContextPainter** | void |  |
| **Start** *(+2 overloads)* | void |  |
| **StartReverse** *(+1 overloads)* | void |  |
| **Stop** | void |  |

---

### Method Details

#### Continue

**Continue**(): void


---

#### CorrectAnimationTimes `static`

**CorrectAnimationTimes**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **geoms**: List<[StiGeom](../../../Stimulsoft/Base/Context/StiGeom.md)>): void

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **geoms** (List<[StiGeom](../../../Stimulsoft/Base/Context/StiGeom.md)>)  


---

#### Dispose

**Dispose**(): void


---

#### Finish

**Finish**(): void


---

#### GetAnimationAngle `static`

**GetAnimationAngle**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **geoms**: List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>, **animation**: [StiPieSegmentAnimation](../../../Stimulsoft/Base/Context/Animation/StiPieSegmentAnimation.md)): List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **geoms** (List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>)  
- **animation** ([StiPieSegmentAnimation](../../../Stimulsoft/Base/Context/Animation/StiPieSegmentAnimation.md))  

**Returns** List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>

---

**GetAnimationAngle**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **geom**: [StiPieSegmentGeom](../../../Stimulsoft/Base/Context/StiPieSegmentGeom.md), **animation**: [StiPieSegmentAnimation](../../../Stimulsoft/Base/Context/Animation/StiPieSegmentAnimation.md)): [StiPieSegmentGeom](../../../Stimulsoft/Base/Context/StiPieSegmentGeom.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **geom** ([StiPieSegmentGeom](../../../Stimulsoft/Base/Context/StiPieSegmentGeom.md))  
- **animation** ([StiPieSegmentAnimation](../../../Stimulsoft/Base/Context/Animation/StiPieSegmentAnimation.md))  

**Returns** [StiPieSegmentGeom](../../../Stimulsoft/Base/Context/StiPieSegmentGeom.md)


---

#### GetAnimationOpacity `static`

**GetAnimationOpacity**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md), **animation**: [StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md)): [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** ([StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md))  
- **animation** ([StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md))  

**Returns** [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md)

---

**GetAnimationOpacity**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: Color, **animation**: [StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md)): Color

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** (Color)  
- **animation** ([StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md))  

**Returns** Color

---

**GetAnimationOpacity**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: object, **animation**: [StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md)): object

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** (object)  
- **animation** ([StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md))  

**Returns** object

---

**GetAnimationOpacity**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md), **animation**: [StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md)): [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** ([StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md))  
- **animation** ([StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md))  

**Returns** [StiBrush](../../../../Stimulsoft_Base/Drawing/StiBrush.md)


---

#### GetAnimationPoint `static`

**GetAnimationPoint**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **from**: PointF, **to**: PointF, **animation**: [StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md)): PointF

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **from** (PointF)  
- **to** (PointF)  
- **animation** ([StiAnimation](../../../Stimulsoft/Base/Context/Animation/StiAnimation.md))  

**Returns** PointF

---

**GetAnimationPoint**(**from**: PointF, **to**: PointF, **multiple**: float): PointF

**Parameters**

- **from** (PointF)  
- **to** (PointF)  
- **multiple** (float)  

**Returns** PointF


---

#### GetAnimationPoint3DY `static`

**GetAnimationPoint3DY**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **toPoint**: [StiPoint3D](../../../Chart/StiPoint3D.md), **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): [StiPoint3D](../../../Chart/StiPoint3D.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **toPoint** ([StiPoint3D](../../../Chart/StiPoint3D.md))  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** [StiPoint3D](../../../Chart/StiPoint3D.md)


---

#### GetAnimationPoints `static`

**GetAnimationPoints**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFto, **animation**: [StiPointsAnimation](../../../Stimulsoft/Base/Context/Animation/StiPointsAnimation.md)): PointF[]

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFto)  
- **animation** ([StiPointsAnimation](../../../Stimulsoft/Base/Context/Animation/StiPointsAnimation.md))  

**Returns** PointF[]


---

#### GetAnimationRectangle `static`

**GetAnimationRectangle**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: RectangleF, **from**: RectangleF, **animation**: [StiColumnAnimation](../../../Stimulsoft/Base/Context/Animation/StiColumnAnimation.md)): RectangleF

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** (RectangleF)  
- **from** (RectangleF)  
- **animation** ([StiColumnAnimation](../../../Stimulsoft/Base/Context/Animation/StiColumnAnimation.md))  

**Returns** RectangleF


---

#### GetAnimationRectangle3D `static`

**GetAnimationRectangle3D**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **toRect**: [StiRectangle3D](../../../Chart/StiRectangle3D.md), **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): [StiRectangle3D](../../../Chart/StiRectangle3D.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **toRect** ([StiRectangle3D](../../../Chart/StiRectangle3D.md))  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** [StiRectangle3D](../../../Chart/StiRectangle3D.md)


---

#### GetAnimationRotation `static`

**GetAnimationRotation**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFto, **animation**: [StiRotationAnimation](../../../Stimulsoft/Base/Context/Animation/StiRotationAnimation.md)): PointF[]

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFto)  
- **animation** ([StiRotationAnimation](../../../Stimulsoft/Base/Context/Animation/StiRotationAnimation.md))  

**Returns** PointF[]


---

#### GetAnimationScale `static`

**GetAnimationScale**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: RectangleF, **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): RectangleF

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** (RectangleF)  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** RectangleF

---

**GetAnimationScale**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, **to**: List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>, **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **to** (List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>)  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** List<[StiSegmentGeom](../../../Stimulsoft/Base/Context/StiSegmentGeom.md)>

---

**GetAnimationScale**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFto, **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): PointF[]

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFto)  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** PointF[]


---

#### GetAnimationScale1 `static`

**GetAnimationScale1**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFto, **animation**: [StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md)): PointF[]

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFto)  
- **animation** ([StiScaleAnimation](../../../Stimulsoft/Base/Context/Animation/StiScaleAnimation.md))  

**Returns** PointF[]


---

#### GetAnimationTranslation `static`

**GetAnimationTranslation**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFpoints, **pen**: [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md), **animation**: [StiTranslationAnimation](../../../Stimulsoft/Base/Context/Animation/StiTranslationAnimation.md)): [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md)

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFpoints)  
- **pen** ([StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md))  
- **animation** ([StiTranslationAnimation](../../../Stimulsoft/Base/Context/Animation/StiTranslationAnimation.md))  

**Returns** [StiPenGeom](../../../Stimulsoft/Base/Context/StiPenGeom.md)

---

**GetAnimationTranslation**(**contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>, ****: PointFto, **animation**: [StiTranslationAnimation](../../../Stimulsoft/Base/Context/Animation/StiTranslationAnimation.md)): PointF[]

**Parameters**

- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  
- **** (PointFto)  
- **animation** ([StiTranslationAnimation](../../../Stimulsoft/Base/Context/Animation/StiTranslationAnimation.md))  

**Returns** PointF[]


---

#### IsRunning

**IsRunning**(**component**: StiComponent): bool

**Parameters**

- **component** (StiComponent)  

**Returns** bool


---

#### RegisterContextPainter

**RegisterContextPainter**(**component**: StiComponent, **contextPainter**: [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>): void

**Parameters**

- **component** (StiComponent)  
- **contextPainter** ([IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T>)  


---

#### Start

**Start**(): void

---

**Start**(**isFirstStart**: bool): void

**Parameters**

- **isFirstStart** (bool)  

---

**Start**(**speed**: double): void

**Parameters**

- **speed** (double)  


---

#### StartReverse

**StartReverse**(): void

---

**StartReverse**(**speed**: double): void

**Parameters**

- **speed** (double)  


---

#### Stop

**Stop**(): void


### Events

| Event | Type | Description |
| --- | --- | --- |
| **Animation** | AnimationHandler |  |
| **ReverseEnd** | ReverseEndHandler |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **contextPainter** | [IStiAnimationContextPainter](IStiAnimationContextPainter.md)<T> |  |
| **geoms** | List<T> |  |

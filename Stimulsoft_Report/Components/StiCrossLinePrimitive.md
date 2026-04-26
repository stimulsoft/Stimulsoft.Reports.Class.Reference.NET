---
title: "StiCrossLinePrimitive Class"
---

## StiCrossLinePrimitive Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: [StiLinePrimitive](StiLinePrimitive.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCrossLinePrimitive**() | Creates a new StiCrossLinePrimitive. |
| **StiCrossLinePrimitive**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiCrossLinePrimitive. |

**StiCrossLinePrimitive**()

Creates a new StiCrossLinePrimitive.

---

**StiCrossLinePrimitive**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiCrossLinePrimitive.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanContainIn** | bool | May this container be located in the specified component. |
| **Clone** | object |  |
| **GetEndPoint** *(+1 overloads)* | [StiEndPointPrimitive](StiEndPointPrimitive.md) |  |
| **GetStartPoint** *(+1 overloads)* | [StiStartPointPrimitive](StiStartPointPrimitive.md) |  |
| **OnRemoveComponent** | void |  |

---

### Method Details

#### CanContainIn

**CanContainIn**(**component**: StiComponent): bool

May this container be located in the specified component.

**Parameters**

- **component** (StiComponent) — Component for checking.  

**Returns** bool — true, if this container may is located in the specified component.


---

#### Clone

**Clone**(**cloneProperties**: bool): object

**Parameters**

- **cloneProperties** (bool)  

**Returns** object


---

#### GetEndPoint

**GetEndPoint**(): [StiEndPointPrimitive](StiEndPointPrimitive.md)

**Returns** [StiEndPointPrimitive](StiEndPointPrimitive.md)

---

**GetEndPoint**(**cont**: StiContainer): [StiEndPointPrimitive](StiEndPointPrimitive.md)

**Parameters**

- **cont** (StiContainer)  

**Returns** [StiEndPointPrimitive](StiEndPointPrimitive.md)


---

#### GetStartPoint

**GetStartPoint**(): [StiStartPointPrimitive](StiStartPointPrimitive.md)

**Returns** [StiStartPointPrimitive](StiStartPointPrimitive.md)

---

**GetStartPoint**(**cont**: StiContainer): [StiStartPointPrimitive](StiStartPointPrimitive.md)

**Parameters**

- **cont** (StiContainer)  

**Returns** [StiStartPointPrimitive](StiStartPointPrimitive.md)


---

#### OnRemoveComponent

**OnRemoveComponent**(): void


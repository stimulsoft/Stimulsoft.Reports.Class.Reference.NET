---
title: "Matrix Class"
---

## Matrix Class

**Namespace:** `Stimulsoft.Drawing.Drawing2D`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **Matrix**() |  |
| **Matrix**(float m11, float m12, float m21, float m22, float dx, float dy) |  |

**Matrix**()

---

**Matrix**(**m11**: float, **m12**: float, **m21**: float, **m22**: float, **dx**: float, **dy**: float)

**Parameters**

- **m11** (float)  
- **m12** (float)  
- **m21** (float)  
- **m22** (float)  
- **dx** (float)  
- **dy** (float)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **OffsetX** | float |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | [Matrix](Matrix.md) |  |
| **Dispose** | void |  |
| **Multiply** *(+1 overloads)* | void |  |
| **Reset** | void |  |
| **Rotate** *(+1 overloads)* | void |  |
| **RotateAt** *(+1 overloads)* | void |  |
| **Scale** *(+1 overloads)* | void |  |
| **Shear** | void |  |
| **TransformPoints** | void |  |
| **TransformVectors** | void |  |
| **Translate** *(+1 overloads)* | void |  |

---

### Method Details

#### Clone

**Clone**(): [Matrix](Matrix.md)

**Returns** [Matrix](Matrix.md)


---

#### Dispose

**Dispose**(): void


---

#### Multiply

**Multiply**(**matrix**: [Matrix](Matrix.md)): void

**Parameters**

- **matrix** ([Matrix](Matrix.md))  

---

**Multiply**(**matrix**: [Matrix](Matrix.md), **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **matrix** ([Matrix](Matrix.md))  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### Reset

**Reset**(): void


---

#### Rotate

**Rotate**(**angle**: float): void

**Parameters**

- **angle** (float)  

---

**Rotate**(**angle**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **angle** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### RotateAt

**RotateAt**(**angle**: float, **centerPoint**: PointF): void

**Parameters**

- **angle** (float)  
- **centerPoint** (PointF)  

---

**RotateAt**(**angle**: float, **centerPoint**: PointF, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **angle** (float)  
- **centerPoint** (PointF)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### Scale

**Scale**(**scaleX**: float, **scaleY**: float): void

**Parameters**

- **scaleX** (float)  
- **scaleY** (float)  

---

**Scale**(**scaleX**: float, **scaleY**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **scaleX** (float)  
- **scaleY** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


---

#### Shear

**Shear**(**shearX**: float, **shearY**: float): void

**Parameters**

- **shearX** (float)  
- **shearY** (float)  


---

#### TransformPoints

**TransformPoints**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  


---

#### TransformVectors

**TransformVectors**(****: PointFpoints): void

**Parameters**

- **** (PointFpoints)  


---

#### Translate

**Translate**(**offsetX**: float, **offsetY**: float): void

**Parameters**

- **offsetX** (float)  
- **offsetY** (float)  

---

**Translate**(**offsetX**: float, **offsetY**: float, **order**: System.Drawing.Drawing2D.MatrixOrder): void

**Parameters**

- **offsetX** (float)  
- **offsetY** (float)  
- **order** (System.Drawing.Drawing2D.MatrixOrder)  


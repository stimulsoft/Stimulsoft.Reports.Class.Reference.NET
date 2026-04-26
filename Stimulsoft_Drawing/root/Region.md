---
title: "Region Class"
---

## Region Class

**Namespace:** `Stimulsoft.Drawing`

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **Region**(Rectangle rect) |  |
| **Region**(RectangleF rect) |  |
| **Region**([GraphicsPath](../Drawing2D/GraphicsPath.md) path) |  |

**Region**(**rect**: Rectangle)

**Parameters**

- **rect** (Rectangle)  

---

**Region**(**rect**: RectangleF)

**Parameters**

- **rect** (RectangleF)  

---

**Region**(**path**: [GraphicsPath](../Drawing2D/GraphicsPath.md))

**Parameters**

- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | [Region](Region.md) |  |
| **Dispose** | void |  |
| **Exclude** | void |  |
| **GetBounds** | RectangleF |  |

---

### Method Details

#### Clone

**Clone**(): [Region](Region.md)

**Returns** [Region](Region.md)


---

#### Dispose

**Dispose**(): void


---

#### Exclude

**Exclude**(**path**: [GraphicsPath](../Drawing2D/GraphicsPath.md)): void

**Parameters**

- **path** ([GraphicsPath](../Drawing2D/GraphicsPath.md))  


---

#### GetBounds

**GetBounds**(**g**: [Graphics](Graphics.md)): RectangleF

**Parameters**

- **g** ([Graphics](Graphics.md))  

**Returns** RectangleF


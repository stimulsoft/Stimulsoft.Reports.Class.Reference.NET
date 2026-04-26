---
title: "StiRangeSelectorControl Class"
---

## StiRangeSelectorControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.RangeSelector`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiRangeSelectorControl**([StiControlColorCollection](../StiControlColorCollection.md) colors, StiRangeSelectorElement element) |  |

**StiRangeSelectorControl**(**colors**: [StiControlColorCollection](../StiControlColorCollection.md), **element**: StiRangeSelectorElement)

**Parameters**

- **colors** ([StiControlColorCollection](../StiControlColorCollection.md))  
- **element** (StiRangeSelectorElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Maximum** | decimal |  |
| **Minimum** | decimal |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **OnMouseDown** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnPaint** | void |  |

---

### Method Details

#### OnMouseDown

**OnMouseDown**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnMouseMove

**OnMouseMove**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnMouseUp

**OnMouseUp**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnPaint

**OnPaint**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **FromValueChanged** | EventHandler |  |
| **ToValueChanged** | EventHandler |  |

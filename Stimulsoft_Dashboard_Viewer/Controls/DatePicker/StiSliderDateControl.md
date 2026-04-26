---
title: "StiSliderDateControl Class"
---

## StiSliderDateControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.DatePicker`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSliderDateControl**([StiControlColorCollection](../StiControlColorCollection.md) colors, StiDatePickerElement element) |  |

**StiSliderDateControl**(**colors**: [StiControlColorCollection](../StiControlColorCollection.md), **element**: StiDatePickerElement)

**Parameters**

- **colors** ([StiControlColorCollection](../StiControlColorCollection.md))  
- **element** (StiDatePickerElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HandleBorderSize** `static` | int |  |
| **HandleGap** `static` | int |  |
| **IsRangeSelection** | bool |  |
| **Maximum** | DateTime |  |
| **Minimum** | DateTime |  |
| **TrackSize** `static` | int |  |

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
| **SelectionEndChanged** | EventHandler |  |
| **SelectionStartChanged** | EventHandler |  |

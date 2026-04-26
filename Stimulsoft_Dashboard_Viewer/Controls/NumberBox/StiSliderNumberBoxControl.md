---
title: "StiSliderNumberBoxControl Class"
---

## StiSliderNumberBoxControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.NumberBox`

### Inheritance

Inherits from: Panel  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiSliderNumberBoxControl**([StiControlColorCollection](../StiControlColorCollection.md) colors, StiNumberBoxElement element) |  |

**StiSliderNumberBoxControl**(**colors**: [StiControlColorCollection](../StiControlColorCollection.md), **element**: StiNumberBoxElement)

**Parameters**

- **colors** ([StiControlColorCollection](../StiControlColorCollection.md))  
- **element** (StiNumberBoxElement)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **HandleBorderSize** `static` | int |  |
| **HandleGap** `static` | int |  |
| **IsRangeSelection** | bool |  |
| **Maximum** | decimal |  |
| **Minimum** | decimal |  |
| **TrackSize** `static` | int |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **OnMouseDown** | void |  |
| **OnMouseMove** | void |  |
| **OnMouseUp** | void |  |
| **OnPaint** | void |  |
| **SetMinMaxRange** | void |  |

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


---

#### SetMinMaxRange

**SetMinMaxRange**(**range**: [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md)): void

**Parameters**

- **range** ([DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md))  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **FromValueChanged** | EventHandler |  |
| **ToValueChanged** | EventHandler |  |

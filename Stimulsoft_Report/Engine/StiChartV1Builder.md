---
title: "StiChartV1Builder Class"
---

## StiChartV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiComponentV1Builder](StiComponentV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **Prepare** | void | Prepares a component for rendering. |
| **RenderAtEnd** `static` | void |  |
| **RenderChart** `static` | void |  |

---

### Method Details

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — Rendered component.  
- **outContainer** (StiContainer) — Panel in which rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### RenderAtEnd `static`

**RenderAtEnd**(**masterChart**: [StiChart](../Chart/StiChart.md)): void

**Parameters**

- **masterChart** ([StiChart](../Chart/StiChart.md))  


---

#### RenderChart `static`

**RenderChart**(**masterChart**: [StiChart](../Chart/StiChart.md), **renderedComponent**: StiComponent, **outContainer**: StiContainer): void

**Parameters**

- **masterChart** ([StiChart](../Chart/StiChart.md))  
- **renderedComponent** (StiComponent)  
- **outContainer** (StiContainer)  


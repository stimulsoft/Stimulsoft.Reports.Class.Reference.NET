---
title: "StiHeaderBandV1Builder Class"
---

## StiHeaderBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMaster** `static` | StiComponent | Returns Master component of this component. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent. |
| **Prepare** | void | Prepares a component for rendering. |
| **PrintOddEven** `static` | bool |  |
| **Render** | bool | Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument. |

---

### Method Details

#### GetMaster `static`

**GetMaster**(**masterHeaderBand**: StiHeaderBand): StiComponent

Returns Master component of this component.

**Parameters**

- **masterHeaderBand** (StiHeaderBand)  

**Returns** StiComponent


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A rendered component.  
- **outContainer** (StiContainer) — A panel in which rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### PrintOddEven `static`

**PrintOddEven**(**component**: [IStiPrintOnEvenOddPages](../Components/IStiPrintOnEvenOddPages.md), **printOnEvenOddPagesType**: [StiPrintOnEvenOddPagesType](../Components/StiPrintOnEvenOddPagesType.md)): bool

**Parameters**

- **component** ([IStiPrintOnEvenOddPages](../Components/IStiPrintOnEvenOddPages.md))  
- **printOnEvenOddPagesType** ([StiPrintOnEvenOddPagesType](../Components/StiPrintOnEvenOddPagesType.md))  

**Returns** bool


---

#### Render

**Render**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A component which is being rendered.  
- **outContainer** (StiContainer) — A container in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering of the component is finished or not.


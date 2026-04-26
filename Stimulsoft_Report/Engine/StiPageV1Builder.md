---
title: "StiPageV1Builder Class"
---

## StiPageV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiContainerV1Builder](StiContainerV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. Rendered component is returned in the renderedComponent. |
| **Prepare** | void | Prepares a component for rendering. |
| **UnPrepare** | void | Clears a component after rendering. |

---

### Method Details

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. Rendered component is returned in the renderedComponent.

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

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Clears a component after rendering.

**Parameters**

- **masterComp** (StiComponent)  


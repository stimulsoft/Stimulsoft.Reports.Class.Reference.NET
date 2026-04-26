---
title: "StiPointPrimitiveV1Builder Class"
---

## StiPointPrimitiveV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiComponentV1Builder](StiComponentV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent. |

---

### Method Details

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent events into consideration and without taking Conditions into consideration. The rendered component is returned in the renderedComponent.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A rendered component.  
- **outContainer** (StiContainer) — A panel in which rendering will be done.  

**Returns** bool — Is rendering finished or not.


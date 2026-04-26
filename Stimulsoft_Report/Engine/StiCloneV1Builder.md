---
title: "StiCloneV1Builder Class"
---

## StiCloneV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiContainerV1Builder](StiContainerV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |

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


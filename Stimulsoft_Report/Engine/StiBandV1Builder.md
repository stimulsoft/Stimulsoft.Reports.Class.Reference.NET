---
title: "StiBandV1Builder Class"
---

## StiBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiContainerV1Builder](StiContainerV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetChildBands** `static` | StiComponentsCollection | Returns child bands. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **RenderChilds** `static` | bool | Render childs bands. |

---

### Method Details

#### GetChildBands `static`

**GetChildBands**(**masterBand**: StiBand): StiComponentsCollection

Returns child bands.

**Parameters**

- **masterBand** (StiBand)  

**Returns** StiComponentsCollection


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — Rendered component.  
- **outContainer** (StiContainer) — Panel in which rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### RenderChilds `static`

**RenderChilds**(**masterBand**: StiBand, **outContainer**: StiContainer): bool

Render childs bands.

**Parameters**

- **masterBand** (StiBand)  
- **outContainer** (StiContainer)  

**Returns** bool


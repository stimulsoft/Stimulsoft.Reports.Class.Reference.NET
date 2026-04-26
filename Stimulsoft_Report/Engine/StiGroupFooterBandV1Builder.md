---
title: "StiGroupFooterBandV1Builder Class"
---

## StiGroupFooterBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Render** | bool | Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument. |

---

### Method Details

#### Render

**Render**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A component which is being rendered.  
- **outContainer** (StiContainer) — A container in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering of the component is finished or not.


---
title: "StiContainerV1Builder Class"
---

## StiContainerV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiComponentV1Builder](StiComponentV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckBandsAtBottom** | void |  |
| **FirstComponent** | void | Move to the first component. |
| **GetClones** `static` | StiComponentsCollection | Returns a collection of clones. |
| **GetRenderContainer** `static` | StiContainer | Returns a panel for the component rendering. |
| **InternalCoreRenderContainer** | bool | Renders a container in the specified place. This is a basic method of container rendering. |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **InternalRenderContainer** | bool | Renders a container without invokes events. These methods process bands at bottom. |
| **NextComponent** | void | Move to the next component. |
| **Prepare** | void | Prepares a component for rendering. |
| **RenderContainer** | bool | Renders a container without invokes events. This method processes Childs of container. Method calls InternalRenderContainer. |
| **UnPrepare** | void | Clears a component after rendering. |

---

### Method Details

#### CheckBandsAtBottom

**CheckBandsAtBottom**(**masterContainer**: StiContainer, **renderedComponent**: StiComponent, **outContainer**: StiContainer): void

**Parameters**

- **masterContainer** (StiContainer)  
- **renderedComponent** (StiComponent)  
- **outContainer** (StiContainer)  


---

#### FirstComponent

**FirstComponent**(**masterContainer**: StiContainer): void

Move to the first component.

**Parameters**

- **masterContainer** (StiContainer)  


---

#### GetClones `static`

**GetClones**(**masterContainer**: StiContainer): StiComponentsCollection

Returns a collection of clones.

**Parameters**

- **masterContainer** (StiContainer)  

**Returns** StiComponentsCollection — Components collection.


---

#### GetRenderContainer `static`

**GetRenderContainer**(**outContainer**: StiContainer, **comp**: StiComponent): StiContainer

Returns a panel for the component rendering.

**Parameters**

- **outContainer** (StiContainer)  
- **comp** (StiComponent) — The component that is a base for a component preparation.  

**Returns** StiContainer — Panel for rendering.


---

#### InternalCoreRenderContainer

**InternalCoreRenderContainer**(**masterContainer**: StiContainer, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a container in the specified place. This is a basic method of container rendering.

**Parameters**

- **masterContainer** (StiContainer)  
- **renderedComponent** (StiComponent) — Rendered container.  
- **outContainer** (StiContainer) — Container for rendering.  

**Returns** bool — If the container is rendered completely then true.


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A rendered component.  
- **outContainer** (StiContainer) — A panel in what rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### InternalRenderContainer

**InternalRenderContainer**(**masterContainer**: StiContainer, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a container without invokes events. These methods process bands at bottom.

**Parameters**

- **masterContainer** (StiContainer)  
- **renderedComponent** (StiComponent) — A rendered container.  
- **outContainer** (StiContainer) — A container for rendering.  

**Returns** bool — If a container is rendered completely then true.


---

#### NextComponent

**NextComponent**(**masterContainer**: StiContainer): void

Move to the next component.

**Parameters**

- **masterContainer** (StiContainer)  


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### RenderContainer

**RenderContainer**(**masterContainer**: StiContainer, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a container without invokes events. This method processes Childs of container. Method calls InternalRenderContainer.

**Parameters**

- **masterContainer** (StiContainer)  
- **renderedComponent** (StiComponent) — A rendered container.  
- **outContainer** (StiContainer) — A container for rendering.  

**Returns** bool — If a container is rendered completely then true.


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Clears a component after rendering.

**Parameters**

- **masterComp** (StiComponent)  


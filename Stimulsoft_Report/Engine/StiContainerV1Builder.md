---
title: "StiContainerV1Builder Class"
---

## StiContainerV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiContainerV1Builder
```

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
